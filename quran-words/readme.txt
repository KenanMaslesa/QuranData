
   pages = quran.words.json

HTML:
      <div *ngFor="let page of pages; let pageIndex = index">
        <div dir="rtl" lang="ar">
          <div class="ayeLine" *ngFor="let ayah of page;">
            <i class="p{{pageIndex+1}}" *ngFor="let word of ayah.words;" [innerHtml]="word"></i>
          </div>
        </div>
      </div>

SCSS:
.ayeLine {
  cursor: default;
  position: relative;
  transition: .3s;
  padding: 4px 0;
  border: 1px solid transparent;
  border-radius: .25rem;
  color: #000;
  min-height: 60px;

  &:last-of-type {
    margin-bottom: 5px;
  }

  &:first-of-type {
    margin-top: 10px;
  }

  @media(max-width: 768px){
    min-height: 40px;
  }

  i{
    font-style: normal;
    line-height: 49px;
    height: 50px;
    font-size: 45px;
    padding-left: 1px;

    @media(max-width: 768px){
      font-size: 23px;
      line-height: 29px;
      height: 30px;
    }

  &.active, &.hover{
      color: var(--ion-color-primary);
      cursor: pointer;
    }

    &:hover {
      color: var(--ion-color-primary);
    }
  }
}
