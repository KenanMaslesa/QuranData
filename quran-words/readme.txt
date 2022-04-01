
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
i{
  font-weight: 400;
  font-style: normal;
  display: inline-block;
  transition: .3s;
  border-bottom: 1px solid transparent;
  opacity: 1;
  line-height: 49px;
  height: 50px;
  font-size: 45px;
  padding-left: 1px;
  outline: none;
  cursor: pointer;

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
