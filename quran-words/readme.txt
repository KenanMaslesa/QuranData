
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

@font-face {
  font-display: block;
  font-family: p1;
  src: url(fonts/p1.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p2;
  src: url(fonts/p2.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p3;
  src: url(fonts/p3.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p4;
  src: url(fonts/p4.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p5;
  src: url(fonts/p5.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p6;
  src: url(fonts/p6.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p7;
  src: url(fonts/p7.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p8;
  src: url(fonts/p8.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p9;
  src: url(fonts/p9.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p10;
  src: url(fonts/p10.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p11;
  src: url(fonts/p11.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p12;
  src: url(fonts/p12.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p13;
  src: url(fonts/p13.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p14;
  src: url(fonts/p14.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p15;
  src: url(fonts/p15.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p16;
  src: url(fonts/p16.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p17;
  src: url(fonts/p17.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p18;
  src: url(fonts/p18.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p19;
  src: url(fonts/p19.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p20;
  src: url(fonts/p20.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p21;
  src: url(fonts/p21.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p22;
  src: url(fonts/p22.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p23;
  src: url(fonts/p23.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p24;
  src: url(fonts/p24.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p25;
  src: url(fonts/p25.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p26;
  src: url(fonts/p26.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p27;
  src: url(fonts/p27.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p28;
  src: url(fonts/p28.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p29;
  src: url(fonts/p29.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p30;
  src: url(fonts/p30.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p31;
  src: url(fonts/p31.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p32;
  src: url(fonts/p32.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p33;
  src: url(fonts/p33.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p34;
  src: url(fonts/p34.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p35;
  src: url(fonts/p35.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p36;
  src: url(fonts/p36.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p37;
  src: url(fonts/p37.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p38;
  src: url(fonts/p38.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p39;
  src: url(fonts/p39.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p40;
  src: url(fonts/p40.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p41;
  src: url(fonts/p41.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p42;
  src: url(fonts/p42.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p43;
  src: url(fonts/p43.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p44;
  src: url(fonts/p44.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p45;
  src: url(fonts/p45.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p46;
  src: url(fonts/p46.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p47;
  src: url(fonts/p47.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p48;
  src: url(fonts/p48.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p49;
  src: url(fonts/p49.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p50;
  src: url(fonts/p50.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p51;
  src: url(fonts/p51.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p52;
  src: url(fonts/p52.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p53;
  src: url(fonts/p53.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p54;
  src: url(fonts/p54.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p55;
  src: url(fonts/p55.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p56;
  src: url(fonts/p56.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p57;
  src: url(fonts/p57.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p58;
  src: url(fonts/p58.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p59;
  src: url(fonts/p59.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p60;
  src: url(fonts/p60.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p61;
  src: url(fonts/p61.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p62;
  src: url(fonts/p62.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p63;
  src: url(fonts/p63.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p64;
  src: url(fonts/p64.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p65;
  src: url(fonts/p65.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p66;
  src: url(fonts/p66.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p67;
  src: url(fonts/p67.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p68;
  src: url(fonts/p68.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p69;
  src: url(fonts/p69.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p70;
  src: url(fonts/p70.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p71;
  src: url(fonts/p71.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p72;
  src: url(fonts/p72.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p73;
  src: url(fonts/p73.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p74;
  src: url(fonts/p74.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p75;
  src: url(fonts/p75.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p76;
  src: url(fonts/p76.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p77;
  src: url(fonts/p77.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p78;
  src: url(fonts/p78.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p79;
  src: url(fonts/p79.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p80;
  src: url(fonts/p80.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p81;
  src: url(fonts/p81.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p82;
  src: url(fonts/p82.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p83;
  src: url(fonts/p83.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p84;
  src: url(fonts/p84.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p85;
  src: url(fonts/p85.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p86;
  src: url(fonts/p86.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p87;
  src: url(fonts/p87.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p88;
  src: url(fonts/p88.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p89;
  src: url(fonts/p89.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p90;
  src: url(fonts/p90.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p91;
  src: url(fonts/p91.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p92;
  src: url(fonts/p92.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p93;
  src: url(fonts/p93.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p94;
  src: url(fonts/p94.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p95;
  src: url(fonts/p95.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p96;
  src: url(fonts/p96.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p97;
  src: url(fonts/p97.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p98;
  src: url(fonts/p98.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p99;
  src: url(fonts/p99.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p100;
  src: url(fonts/p100.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p101;
  src: url(fonts/p101.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p102;
  src: url(fonts/p102.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p103;
  src: url(fonts/p103.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p104;
  src: url(fonts/p104.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p105;
  src: url(fonts/p105.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p106;
  src: url(fonts/p106.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p107;
  src: url(fonts/p107.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p108;
  src: url(fonts/p108.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p109;
  src: url(fonts/p109.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p110;
  src: url(fonts/p110.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p111;
  src: url(fonts/p111.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p112;
  src: url(fonts/p112.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p113;
  src: url(fonts/p113.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p114;
  src: url(fonts/p114.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p115;
  src: url(fonts/p115.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p116;
  src: url(fonts/p116.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p117;
  src: url(fonts/p117.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p118;
  src: url(fonts/p118.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p119;
  src: url(fonts/p119.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p120;
  src: url(fonts/p120.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p121;
  src: url(fonts/p121.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p122;
  src: url(fonts/p122.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p123;
  src: url(fonts/p123.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p124;
  src: url(fonts/p124.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p125;
  src: url(fonts/p125.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p126;
  src: url(fonts/p126.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p127;
  src: url(fonts/p127.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p128;
  src: url(fonts/p128.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p129;
  src: url(fonts/p129.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p130;
  src: url(fonts/p130.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p131;
  src: url(fonts/p131.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p132;
  src: url(fonts/p132.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p133;
  src: url(fonts/p133.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p134;
  src: url(fonts/p134.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p135;
  src: url(fonts/p135.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p136;
  src: url(fonts/p136.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p137;
  src: url(fonts/p137.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p138;
  src: url(fonts/p138.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p139;
  src: url(fonts/p139.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p140;
  src: url(fonts/p140.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p141;
  src: url(fonts/p141.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p142;
  src: url(fonts/p142.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p143;
  src: url(fonts/p143.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p144;
  src: url(fonts/p144.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p145;
  src: url(fonts/p145.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p146;
  src: url(fonts/p146.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p147;
  src: url(fonts/p147.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p148;
  src: url(fonts/p148.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p149;
  src: url(fonts/p149.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p150;
  src: url(fonts/p150.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p151;
  src: url(fonts/p151.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p152;
  src: url(fonts/p152.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p153;
  src: url(fonts/p153.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p154;
  src: url(fonts/p154.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p155;
  src: url(fonts/p155.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p156;
  src: url(fonts/p156.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p157;
  src: url(fonts/p157.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p158;
  src: url(fonts/p158.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p159;
  src: url(fonts/p159.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p160;
  src: url(fonts/p160.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p161;
  src: url(fonts/p161.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p162;
  src: url(fonts/p162.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p163;
  src: url(fonts/p163.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p164;
  src: url(fonts/p164.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p165;
  src: url(fonts/p165.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p166;
  src: url(fonts/p166.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p167;
  src: url(fonts/p167.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p168;
  src: url(fonts/p168.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p169;
  src: url(fonts/p169.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p170;
  src: url(fonts/p170.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p171;
  src: url(fonts/p171.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p172;
  src: url(fonts/p172.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p173;
  src: url(fonts/p173.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p174;
  src: url(fonts/p174.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p175;
  src: url(fonts/p175.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p176;
  src: url(fonts/p176.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p177;
  src: url(fonts/p177.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p178;
  src: url(fonts/p178.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p179;
  src: url(fonts/p179.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p180;
  src: url(fonts/p180.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p181;
  src: url(fonts/p181.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p182;
  src: url(fonts/p182.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p183;
  src: url(fonts/p183.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p184;
  src: url(fonts/p184.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p185;
  src: url(fonts/p185.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p186;
  src: url(fonts/p186.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p187;
  src: url(fonts/p187.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p188;
  src: url(fonts/p188.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p189;
  src: url(fonts/p189.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p190;
  src: url(fonts/p190.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p191;
  src: url(fonts/p191.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p192;
  src: url(fonts/p192.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p193;
  src: url(fonts/p193.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p194;
  src: url(fonts/p194.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p195;
  src: url(fonts/p195.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p196;
  src: url(fonts/p196.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p197;
  src: url(fonts/p197.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p198;
  src: url(fonts/p198.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p199;
  src: url(fonts/p199.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p200;
  src: url(fonts/p200.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p201;
  src: url(fonts/p201.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p202;
  src: url(fonts/p202.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p203;
  src: url(fonts/p203.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p204;
  src: url(fonts/p204.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p205;
  src: url(fonts/p205.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p206;
  src: url(fonts/p206.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p207;
  src: url(fonts/p207.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p208;
  src: url(fonts/p208.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p209;
  src: url(fonts/p209.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p210;
  src: url(fonts/p210.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p211;
  src: url(fonts/p211.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p212;
  src: url(fonts/p212.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p213;
  src: url(fonts/p213.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p214;
  src: url(fonts/p214.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p215;
  src: url(fonts/p215.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p216;
  src: url(fonts/p216.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p217;
  src: url(fonts/p217.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p218;
  src: url(fonts/p218.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p219;
  src: url(fonts/p219.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p220;
  src: url(fonts/p220.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p221;
  src: url(fonts/p221.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p222;
  src: url(fonts/p222.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p223;
  src: url(fonts/p223.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p224;
  src: url(fonts/p224.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p225;
  src: url(fonts/p225.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p226;
  src: url(fonts/p226.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p227;
  src: url(fonts/p227.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p228;
  src: url(fonts/p228.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p229;
  src: url(fonts/p229.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p230;
  src: url(fonts/p230.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p231;
  src: url(fonts/p231.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p232;
  src: url(fonts/p232.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p233;
  src: url(fonts/p233.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p234;
  src: url(fonts/p234.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p235;
  src: url(fonts/p235.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p236;
  src: url(fonts/p236.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p237;
  src: url(fonts/p237.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p238;
  src: url(fonts/p238.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p239;
  src: url(fonts/p239.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p240;
  src: url(fonts/p240.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p241;
  src: url(fonts/p241.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p242;
  src: url(fonts/p242.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p243;
  src: url(fonts/p243.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p244;
  src: url(fonts/p244.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p245;
  src: url(fonts/p245.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p246;
  src: url(fonts/p246.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p247;
  src: url(fonts/p247.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p248;
  src: url(fonts/p248.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p249;
  src: url(fonts/p249.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p250;
  src: url(fonts/p250.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p251;
  src: url(fonts/p251.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p252;
  src: url(fonts/p252.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p253;
  src: url(fonts/p253.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p254;
  src: url(fonts/p254.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p255;
  src: url(fonts/p255.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p256;
  src: url(fonts/p256.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p257;
  src: url(fonts/p257.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p258;
  src: url(fonts/p258.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p259;
  src: url(fonts/p259.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p260;
  src: url(fonts/p260.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p261;
  src: url(fonts/p261.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p262;
  src: url(fonts/p262.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p263;
  src: url(fonts/p263.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p264;
  src: url(fonts/p264.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p265;
  src: url(fonts/p265.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p266;
  src: url(fonts/p266.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p267;
  src: url(fonts/p267.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p268;
  src: url(fonts/p268.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p269;
  src: url(fonts/p269.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p270;
  src: url(fonts/p270.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p271;
  src: url(fonts/p271.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p272;
  src: url(fonts/p272.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p273;
  src: url(fonts/p273.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p274;
  src: url(fonts/p274.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p275;
  src: url(fonts/p275.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p276;
  src: url(fonts/p276.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p277;
  src: url(fonts/p277.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p278;
  src: url(fonts/p278.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p279;
  src: url(fonts/p279.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p280;
  src: url(fonts/p280.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p281;
  src: url(fonts/p281.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p282;
  src: url(fonts/p282.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p283;
  src: url(fonts/p283.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p284;
  src: url(fonts/p284.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p285;
  src: url(fonts/p285.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p286;
  src: url(fonts/p286.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p287;
  src: url(fonts/p287.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p288;
  src: url(fonts/p288.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p289;
  src: url(fonts/p289.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p290;
  src: url(fonts/p290.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p291;
  src: url(fonts/p291.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p292;
  src: url(fonts/p292.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p293;
  src: url(fonts/p293.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p294;
  src: url(fonts/p294.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p295;
  src: url(fonts/p295.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p296;
  src: url(fonts/p296.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p297;
  src: url(fonts/p297.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p298;
  src: url(fonts/p298.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p299;
  src: url(fonts/p299.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p300;
  src: url(fonts/p300.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p301;
  src: url(fonts/p301.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p302;
  src: url(fonts/p302.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p303;
  src: url(fonts/p303.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p304;
  src: url(fonts/p304.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p305;
  src: url(fonts/p305.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p306;
  src: url(fonts/p306.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p307;
  src: url(fonts/p307.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p308;
  src: url(fonts/p308.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p309;
  src: url(fonts/p309.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p310;
  src: url(fonts/p310.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p311;
  src: url(fonts/p311.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p312;
  src: url(fonts/p312.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p313;
  src: url(fonts/p313.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p314;
  src: url(fonts/p314.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p315;
  src: url(fonts/p315.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p316;
  src: url(fonts/p316.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p317;
  src: url(fonts/p317.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p318;
  src: url(fonts/p318.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p319;
  src: url(fonts/p319.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p320;
  src: url(fonts/p320.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p321;
  src: url(fonts/p321.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p322;
  src: url(fonts/p322.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p323;
  src: url(fonts/p323.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p324;
  src: url(fonts/p324.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p325;
  src: url(fonts/p325.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p326;
  src: url(fonts/p326.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p327;
  src: url(fonts/p327.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p328;
  src: url(fonts/p328.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p329;
  src: url(fonts/p329.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p330;
  src: url(fonts/p330.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p331;
  src: url(fonts/p331.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p332;
  src: url(fonts/p332.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p333;
  src: url(fonts/p333.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p334;
  src: url(fonts/p334.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p335;
  src: url(fonts/p335.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p336;
  src: url(fonts/p336.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p337;
  src: url(fonts/p337.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p338;
  src: url(fonts/p338.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p339;
  src: url(fonts/p339.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p340;
  src: url(fonts/p340.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p341;
  src: url(fonts/p341.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p342;
  src: url(fonts/p342.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p343;
  src: url(fonts/p343.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p344;
  src: url(fonts/p344.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p345;
  src: url(fonts/p345.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p346;
  src: url(fonts/p346.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p347;
  src: url(fonts/p347.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p348;
  src: url(fonts/p348.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p349;
  src: url(fonts/p349.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p350;
  src: url(fonts/p350.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p351;
  src: url(fonts/p351.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p352;
  src: url(fonts/p352.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p353;
  src: url(fonts/p353.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p354;
  src: url(fonts/p354.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p355;
  src: url(fonts/p355.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p356;
  src: url(fonts/p356.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p357;
  src: url(fonts/p357.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p358;
  src: url(fonts/p358.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p359;
  src: url(fonts/p359.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p360;
  src: url(fonts/p360.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p361;
  src: url(fonts/p361.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p362;
  src: url(fonts/p362.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p363;
  src: url(fonts/p363.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p364;
  src: url(fonts/p364.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p365;
  src: url(fonts/p365.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p366;
  src: url(fonts/p366.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p367;
  src: url(fonts/p367.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p368;
  src: url(fonts/p368.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p369;
  src: url(fonts/p369.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p370;
  src: url(fonts/p370.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p371;
  src: url(fonts/p371.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p372;
  src: url(fonts/p372.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p373;
  src: url(fonts/p373.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p374;
  src: url(fonts/p374.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p375;
  src: url(fonts/p375.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p376;
  src: url(fonts/p376.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p377;
  src: url(fonts/p377.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p378;
  src: url(fonts/p378.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p379;
  src: url(fonts/p379.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p380;
  src: url(fonts/p380.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p381;
  src: url(fonts/p381.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p382;
  src: url(fonts/p382.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p383;
  src: url(fonts/p383.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p384;
  src: url(fonts/p384.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p385;
  src: url(fonts/p385.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p386;
  src: url(fonts/p386.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p387;
  src: url(fonts/p387.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p388;
  src: url(fonts/p388.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p389;
  src: url(fonts/p389.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p390;
  src: url(fonts/p390.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p391;
  src: url(fonts/p391.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p392;
  src: url(fonts/p392.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p393;
  src: url(fonts/p393.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p394;
  src: url(fonts/p394.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p395;
  src: url(fonts/p395.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p396;
  src: url(fonts/p396.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p397;
  src: url(fonts/p397.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p398;
  src: url(fonts/p398.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p399;
  src: url(fonts/p399.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p400;
  src: url(fonts/p400.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p401;
  src: url(fonts/p401.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p402;
  src: url(fonts/p402.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p403;
  src: url(fonts/p403.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p404;
  src: url(fonts/p404.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p405;
  src: url(fonts/p405.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p406;
  src: url(fonts/p406.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p407;
  src: url(fonts/p407.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p408;
  src: url(fonts/p408.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p409;
  src: url(fonts/p409.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p410;
  src: url(fonts/p410.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p411;
  src: url(fonts/p411.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p412;
  src: url(fonts/p412.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p413;
  src: url(fonts/p413.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p414;
  src: url(fonts/p414.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p415;
  src: url(fonts/p415.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p416;
  src: url(fonts/p416.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p417;
  src: url(fonts/p417.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p418;
  src: url(fonts/p418.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p419;
  src: url(fonts/p419.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p420;
  src: url(fonts/p420.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p421;
  src: url(fonts/p421.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p422;
  src: url(fonts/p422.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p423;
  src: url(fonts/p423.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p424;
  src: url(fonts/p424.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p425;
  src: url(fonts/p425.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p426;
  src: url(fonts/p426.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p427;
  src: url(fonts/p427.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p428;
  src: url(fonts/p428.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p429;
  src: url(fonts/p429.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p430;
  src: url(fonts/p430.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p431;
  src: url(fonts/p431.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p432;
  src: url(fonts/p432.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p433;
  src: url(fonts/p433.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p434;
  src: url(fonts/p434.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p435;
  src: url(fonts/p435.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p436;
  src: url(fonts/p436.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p437;
  src: url(fonts/p437.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p438;
  src: url(fonts/p438.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p439;
  src: url(fonts/p439.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p440;
  src: url(fonts/p440.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p441;
  src: url(fonts/p441.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p442;
  src: url(fonts/p442.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p443;
  src: url(fonts/p443.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p444;
  src: url(fonts/p444.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p445;
  src: url(fonts/p445.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p446;
  src: url(fonts/p446.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p447;
  src: url(fonts/p447.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p448;
  src: url(fonts/p448.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p449;
  src: url(fonts/p449.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p450;
  src: url(fonts/p450.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p451;
  src: url(fonts/p451.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p452;
  src: url(fonts/p452.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p453;
  src: url(fonts/p453.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p454;
  src: url(fonts/p454.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p455;
  src: url(fonts/p455.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p456;
  src: url(fonts/p456.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p457;
  src: url(fonts/p457.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p458;
  src: url(fonts/p458.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p459;
  src: url(fonts/p459.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p460;
  src: url(fonts/p460.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p461;
  src: url(fonts/p461.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p462;
  src: url(fonts/p462.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p463;
  src: url(fonts/p463.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p464;
  src: url(fonts/p464.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p465;
  src: url(fonts/p465.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p466;
  src: url(fonts/p466.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p467;
  src: url(fonts/p467.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p468;
  src: url(fonts/p468.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p469;
  src: url(fonts/p469.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p470;
  src: url(fonts/p470.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p471;
  src: url(fonts/p471.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p472;
  src: url(fonts/p472.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p473;
  src: url(fonts/p473.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p474;
  src: url(fonts/p474.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p475;
  src: url(fonts/p475.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p476;
  src: url(fonts/p476.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p477;
  src: url(fonts/p477.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p478;
  src: url(fonts/p478.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p479;
  src: url(fonts/p479.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p480;
  src: url(fonts/p480.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p481;
  src: url(fonts/p481.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p482;
  src: url(fonts/p482.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p483;
  src: url(fonts/p483.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p484;
  src: url(fonts/p484.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p485;
  src: url(fonts/p485.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p486;
  src: url(fonts/p486.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p487;
  src: url(fonts/p487.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p488;
  src: url(fonts/p488.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p489;
  src: url(fonts/p489.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p490;
  src: url(fonts/p490.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p491;
  src: url(fonts/p491.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p492;
  src: url(fonts/p492.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p493;
  src: url(fonts/p493.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p494;
  src: url(fonts/p494.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p495;
  src: url(fonts/p495.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p496;
  src: url(fonts/p496.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p497;
  src: url(fonts/p497.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p498;
  src: url(fonts/p498.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p499;
  src: url(fonts/p499.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p500;
  src: url(fonts/p500.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p501;
  src: url(fonts/p501.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p502;
  src: url(fonts/p502.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p503;
  src: url(fonts/p503.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p504;
  src: url(fonts/p504.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p505;
  src: url(fonts/p505.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p506;
  src: url(fonts/p506.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p507;
  src: url(fonts/p507.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p508;
  src: url(fonts/p508.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p509;
  src: url(fonts/p509.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p510;
  src: url(fonts/p510.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p511;
  src: url(fonts/p511.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p512;
  src: url(fonts/p512.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p513;
  src: url(fonts/p513.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p514;
  src: url(fonts/p514.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p515;
  src: url(fonts/p515.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p516;
  src: url(fonts/p516.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p517;
  src: url(fonts/p517.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p518;
  src: url(fonts/p518.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p519;
  src: url(fonts/p519.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p520;
  src: url(fonts/p520.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p521;
  src: url(fonts/p521.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p522;
  src: url(fonts/p522.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p523;
  src: url(fonts/p523.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p524;
  src: url(fonts/p524.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p525;
  src: url(fonts/p525.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p526;
  src: url(fonts/p526.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p527;
  src: url(fonts/p527.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p528;
  src: url(fonts/p528.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p529;
  src: url(fonts/p529.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p530;
  src: url(fonts/p530.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p531;
  src: url(fonts/p531.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p532;
  src: url(fonts/p532.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p533;
  src: url(fonts/p533.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p534;
  src: url(fonts/p534.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p535;
  src: url(fonts/p535.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p536;
  src: url(fonts/p536.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p537;
  src: url(fonts/p537.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p538;
  src: url(fonts/p538.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p539;
  src: url(fonts/p539.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p540;
  src: url(fonts/p540.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p541;
  src: url(fonts/p541.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p542;
  src: url(fonts/p542.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p543;
  src: url(fonts/p543.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p544;
  src: url(fonts/p544.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p545;
  src: url(fonts/p545.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p546;
  src: url(fonts/p546.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p547;
  src: url(fonts/p547.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p548;
  src: url(fonts/p548.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p549;
  src: url(fonts/p549.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p550;
  src: url(fonts/p550.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p551;
  src: url(fonts/p551.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p552;
  src: url(fonts/p552.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p553;
  src: url(fonts/p553.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p554;
  src: url(fonts/p554.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p555;
  src: url(fonts/p555.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p556;
  src: url(fonts/p556.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p557;
  src: url(fonts/p557.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p558;
  src: url(fonts/p558.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p559;
  src: url(fonts/p559.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p560;
  src: url(fonts/p560.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p561;
  src: url(fonts/p561.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p562;
  src: url(fonts/p562.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p563;
  src: url(fonts/p563.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p564;
  src: url(fonts/p564.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p565;
  src: url(fonts/p565.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p566;
  src: url(fonts/p566.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p567;
  src: url(fonts/p567.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p568;
  src: url(fonts/p568.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p569;
  src: url(fonts/p569.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p570;
  src: url(fonts/p570.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p571;
  src: url(fonts/p571.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p572;
  src: url(fonts/p572.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p573;
  src: url(fonts/p573.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p574;
  src: url(fonts/p574.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p575;
  src: url(fonts/p575.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p576;
  src: url(fonts/p576.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p577;
  src: url(fonts/p577.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p578;
  src: url(fonts/p578.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p579;
  src: url(fonts/p579.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p580;
  src: url(fonts/p580.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p581;
  src: url(fonts/p581.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p582;
  src: url(fonts/p582.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p583;
  src: url(fonts/p583.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p584;
  src: url(fonts/p584.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p585;
  src: url(fonts/p585.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p586;
  src: url(fonts/p586.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p587;
  src: url(fonts/p587.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p588;
  src: url(fonts/p588.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p589;
  src: url(fonts/p589.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p590;
  src: url(fonts/p590.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p591;
  src: url(fonts/p591.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p592;
  src: url(fonts/p592.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p593;
  src: url(fonts/p593.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p594;
  src: url(fonts/p594.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p595;
  src: url(fonts/p595.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p596;
  src: url(fonts/p596.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p597;
  src: url(fonts/p597.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p598;
  src: url(fonts/p598.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p599;
  src: url(fonts/p599.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p600;
  src: url(fonts/p600.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p601;
  src: url(fonts/p601.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p602;
  src: url(fonts/p602.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p603;
  src: url(fonts/p603.ttf) format("truetype")
}

@font-face {
  font-display: block;
  font-family: p604;
  src: url(fonts/p604.ttf) format("truetype")
}

@font-face {
  font-family: bismillah;
  src: url(fonts/bismillah.eot);
  src: url(fonts/bismillah.eot) format("embedded-opentype") , url(fonts/bismillah.ttf) format("truetype") , url(fonts/bismillah.woff) format("woff") , url(https://salamquran.com/images/bismillah/bismillah.svg) format("svg");
  font-weight: 400;
  font-display: block
}

@font-face {
  font-family: Noorehuda;
  src: url(https://salamquran.com/static/fonts/noorehuda/noorehuda_latest.ttf);
  font-display: block
}

.p1 {
  font-family: p1
}

.p2 {
  font-family:p2
}

.p3 {
  font-family: p3
}

.p4 {
  font-family: p4
}

.p5 {
  font-family: p5
}

.p6 {
  font-family: p6
}

.p7 {
  font-family: p7
}

.p8 {
  font-family: p8
}

.p9 {
  font-family: p9
}

.p10 {
  font-family: p10
}

.p11 {
  font-family: p11
}

.p12 {
  font-family: p12
}

.p13 {
  font-family: p13
}

.p14 {
  font-family: p14
}

.p15 {
  font-family: p15
}

.p16 {
  font-family: p16
}

.p17 {
  font-family: p17
}

.p18 {
  font-family: p18
}

.p19 {
  font-family: p19
}

.p20 {
  font-family: p20
}

.p21 {
  font-family: p21
}

.p22 {
  font-family: p22
}

.p23 {
  font-family: p23
}

.p24 {
  font-family: p24
}

.p25 {
  font-family: p25
}

.p26 {
  font-family: p26
}

.p27 {
  font-family: p27
}

.p28 {
  font-family: p28
}

.p29 {
  font-family: p29
}

.p30 {
  font-family: p30
}

.p31 {
  font-family: p31
}

.p32 {
  font-family: p32
}

.p33 {
  font-family: p33
}

.p34 {
  font-family: p34
}

.p35 {
  font-family: p35
}

.p36 {
  font-family: p36
}

.p37 {
  font-family: p37
}

.p38 {
  font-family: p38
}

.p39 {
  font-family: p39
}

.p40 {
  font-family: p40
}

.p41 {
  font-family: p41
}

.p42 {
  font-family: p42
}

.p43 {
  font-family: p43
}

.p44 {
  font-family: p44
}

.p45 {
  font-family: p45
}

.p46 {
  font-family: p46
}

.p47 {
  font-family: p47
}

.p48 {
  font-family: p48
}

.p49 {
  font-family: p49
}

.p50 {
  font-family: p50
}

.p51 {
  font-family: p51
}

.p52 {
  font-family: p52
}

.p53 {
  font-family: p53
}

.p54 {
  font-family: p54
}

.p55 {
  font-family: p55
}

.p56 {
  font-family: p56
}

.p57 {
  font-family: p57
}

.p58 {
  font-family: p58
}

.p59 {
  font-family: p59
}

.p60 {
  font-family: p60
}

.p61 {
  font-family: p61
}

.p62 {
  font-family: p62
}

.p63 {
  font-family: p63
}

.p64 {
  font-family: p64
}

.p65 {
  font-family: p65
}

.p66 {
  font-family: p66
}

.p67 {
  font-family: p67
}

.p68 {
  font-family: p68
}

.p69 {
  font-family: p69
}

.p70 {
  font-family: p70
}

.p71 {
  font-family: p71
}

.p72 {
  font-family: p72
}

.p73 {
  font-family: p73
}

.p74 {
  font-family: p74
}

.p75 {
  font-family: p75
}

.p76 {
  font-family: p76
}

.p77 {
  font-family: p77
}

.p78 {
  font-family: p78
}

.p79 {
  font-family: p79
}

.p80 {
  font-family: p80
}

.p81 {
  font-family: p81
}

.p82 {
  font-family: p82
}

.p83 {
  font-family: p83
}

.p84 {
  font-family: p84
}

.p85 {
  font-family: p85
}

.p86 {
  font-family: p86
}

.p87 {
  font-family: p87
}

.p88 {
  font-family: p88
}

.p89 {
  font-family: p89
}

.p90 {
  font-family: p90
}

.p91 {
  font-family: p91
}

.p92 {
  font-family: p92
}

.p93 {
  font-family: p93
}

.p94 {
  font-family: p94
}

.p95 {
  font-family: p95
}

.p96 {
  font-family: p96
}

.p97 {
  font-family: p97
}

.p98 {
  font-family: p98
}

.p99 {
  font-family: p99
}

.p100 {
  font-family: p100
}

.p101 {
  font-family: p101
}

.p102 {
  font-family: p102
}

.p103 {
  font-family: p103
}

.p104 {
  font-family: p104
}

.p105 {
  font-family: p105
}

.p106 {
  font-family: p106
}

.p107 {
  font-family: p107
}

.p108 {
  font-family: p108
}

.p109 {
  font-family: p109
}

.p110 {
  font-family: p110
}

.p111 {
  font-family: p111
}

.p112 {
  font-family: p112
}

.p113 {
  font-family: p113
}

.p114 {
  font-family: p114
}

.p115 {
  font-family: p115
}

.p116 {
  font-family: p116
}

.p117 {
  font-family: p117
}

.p118 {
  font-family: p118
}

.p119 {
  font-family: p119
}

.p120 {
  font-family: p120
}

.p121 {
  font-family: p121
}

.p122 {
  font-family: p122
}

.p123 {
  font-family: p123
}

.p124 {
  font-family: p124
}

.p125 {
  font-family: p125
}

.p126 {
  font-family: p126
}

.p127 {
  font-family: p127
}

.p128 {
  font-family: p128
}

.p129 {
  font-family: p129
}

.p130 {
  font-family: p130
}

.p131 {
  font-family: p131
}

.p132 {
  font-family: p132
}

.p133 {
  font-family: p133
}

.p134 {
  font-family: p134
}

.p135 {
  font-family: p135
}

.p136 {
  font-family: p136
}

.p137 {
  font-family: p137
}

.p138 {
  font-family: p138
}

.p139 {
  font-family: p139
}

.p140 {
  font-family: p140
}

.p141 {
  font-family: p141
}

.p142 {
  font-family: p142
}

.p143 {
  font-family: p143
}

.p144 {
  font-family: p144
}

.p145 {
  font-family: p145
}

.p146 {
  font-family: p146
}

.p147 {
  font-family: p147
}

.p148 {
  font-family: p148
}

.p149 {
  font-family: p149
}

.p150 {
  font-family: p150
}

.p151 {
  font-family: p151
}

.p152 {
  font-family: p152
}

.p153 {
  font-family: p153
}

.p154 {
  font-family: p154
}

.p155 {
  font-family: p155
}

.p156 {
  font-family: p156
}

.p157 {
  font-family: p157
}

.p158 {
  font-family: p158
}

.p159 {
  font-family: p159
}

.p160 {
  font-family: p160
}

.p161 {
  font-family: p161
}

.p162 {
  font-family: p162
}

.p163 {
  font-family: p163
}

.p164 {
  font-family: p164
}

.p165 {
  font-family: p165
}

.p166 {
  font-family: p166
}

.p167 {
  font-family: p167
}

.p168 {
  font-family: p168
}

.p169 {
  font-family: p169
}

.p170 {
  font-family: p170
}

.p171 {
  font-family: p171
}

.p172 {
  font-family: p172
}

.p173 {
  font-family: p173
}

.p174 {
  font-family: p174
}

.p175 {
  font-family: p175
}

.p176 {
  font-family: p176
}

.p177 {
  font-family: p177
}

.p178 {
  font-family: p178
}

.p179 {
  font-family: p179
}

.p180 {
  font-family: p180
}

.p181 {
  font-family: p181
}

.p182 {
  font-family: p182
}

.p183 {
  font-family: p183
}

.p184 {
  font-family: p184
}

.p185 {
  font-family: p185
}

.p186 {
  font-family: p186
}

.p187 {
  font-family: p187
}

.p188 {
  font-family: p188
}

.p189 {
  font-family: p189
}

.p190 {
  font-family: p190
}

.p191 {
  font-family: p191
}

.p192 {
  font-family: p192
}

.p193 {
  font-family: p193
}

.p194 {
  font-family: p194
}

.p195 {
  font-family: p195
}

.p196 {
  font-family: p196
}

.p197 {
  font-family: p197
}

.p198 {
  font-family: p198
}

.p199 {
  font-family: p199
}

.p200 {
  font-family: p200
}

.p201 {
  font-family: p201
}

.p202 {
  font-family: p202
}

.p203 {
  font-family: p203
}

.p204 {
  font-family: p204
}

.p205 {
  font-family: p205
}

.p206 {
  font-family: p206
}

.p207 {
  font-family: p207
}

.p208 {
  font-family: p208
}

.p209 {
  font-family: p209
}

.p210 {
  font-family: p210
}

.p211 {
  font-family: p211
}

.p212 {
  font-family: p212
}

.p213 {
  font-family: p213
}

.p214 {
  font-family: p214
}

.p215 {
  font-family: p215
}

.p216 {
  font-family: p216
}

.p217 {
  font-family: p217
}

.p218 {
  font-family: p218
}

.p219 {
  font-family: p219
}

.p220 {
  font-family: p220
}

.p221 {
  font-family: p221
}

.p222 {
  font-family: p222
}

.p223 {
  font-family: p223
}

.p224 {
  font-family: p224
}

.p225 {
  font-family: p225
}

.p226 {
  font-family: p226
}

.p227 {
  font-family: p227
}

.p228 {
  font-family: p228
}

.p229 {
  font-family: p229
}

.p230 {
  font-family: p230
}

.p231 {
  font-family: p231
}

.p232 {
  font-family: p232
}

.p233 {
  font-family: p233
}

.p234 {
  font-family: p234
}

.p235 {
  font-family: p235
}

.p236 {
  font-family: p236
}

.p237 {
  font-family: p237
}

.p238 {
  font-family: p238
}

.p239 {
  font-family: p239
}

.p240 {
  font-family: p240
}

.p241 {
  font-family: p241
}

.p242 {
  font-family: p242
}

.p243 {
  font-family: p243
}

.p244 {
  font-family: p244
}

.p245 {
  font-family: p245
}

.p246 {
  font-family: p246
}

.p247 {
  font-family: p247
}

.p248 {
  font-family: p248
}

.p249 {
  font-family: p249
}

.p250 {
  font-family: p250
}

.p251 {
  font-family: p251
}

.p252 {
  font-family: p252
}

.p253 {
  font-family: p253
}

.p254 {
  font-family: p254
}

.p255 {
  font-family: p255
}

.p256 {
  font-family: p256
}

.p257 {
  font-family: p257
}

.p258 {
  font-family: p258
}

.p259 {
  font-family: p259
}

.p260 {
  font-family: p260
}

.p261 {
  font-family: p261
}

.p262 {
  font-family: p262
}

.p263 {
  font-family: p263
}

.p264 {
  font-family: p264
}

.p265 {
  font-family: p265
}

.p266 {
  font-family: p266
}

.p267 {
  font-family: p267
}

.p268 {
  font-family: p268
}

.p269 {
  font-family: p269
}

.p270 {
  font-family: p270
}

.p271 {
  font-family: p271
}

.p272 {
  font-family: p272
}

.p273 {
  font-family: p273
}

.p274 {
  font-family: p274
}

.p275 {
  font-family: p275
}

.p276 {
  font-family: p276
}

.p277 {
  font-family: p277
}

.p278 {
  font-family: p278
}

.p279 {
  font-family: p279
}

.p280 {
  font-family: p280
}

.p281 {
  font-family: p281
}

.p282 {
  font-family: p282
}

.p283 {
  font-family: p283
}

.p284 {
  font-family: p284
}

.p285 {
  font-family: p285
}

.p286 {
  font-family: p286
}

.p287 {
  font-family: p287
}

.p288 {
  font-family: p288
}

.p289 {
  font-family: p289
}

.p290 {
  font-family: p290
}

.p291 {
  font-family: p291
}

.p292 {
  font-family: p292
}

.p293 {
  font-family: p293
}

.p294 {
  font-family: p294
}

.p295 {
  font-family: p295
}

.p296 {
  font-family: p296
}

.p297 {
  font-family: p297
}

.p298 {
  font-family: p298
}

.p299 {
  font-family: p299
}

.p300 {
  font-family: p300
}

.p301 {
  font-family: p301
}

.p302 {
  font-family: p302
}

.p303 {
  font-family: p303
}

.p304 {
  font-family: p304
}

.p305 {
  font-family: p305
}

.p306 {
  font-family: p306
}

.p307 {
  font-family: p307
}

.p308 {
  font-family: p308
}

.p309 {
  font-family: p309
}

.p310 {
  font-family: p310
}

.p311 {
  font-family: p311
}

.p312 {
  font-family: p312
}

.p313 {
  font-family: p313
}

.p314 {
  font-family: p314
}

.p315 {
  font-family: p315
}

.p316 {
  font-family: p316
}

.p317 {
  font-family: p317
}

.p318 {
  font-family: p318
}

.p319 {
  font-family: p319
}

.p320 {
  font-family: p320
}

.p321 {
  font-family: p321
}

.p322 {
  font-family: p322
}

.p323 {
  font-family: p323
}

.p324 {
  font-family: p324
}

.p325 {
  font-family: p325
}

.p326 {
  font-family: p326
}

.p327 {
  font-family: p327
}

.p328 {
  font-family: p328
}

.p329 {
  font-family: p329
}

.p330 {
  font-family: p330
}

.p331 {
  font-family: p331
}

.p332 {
  font-family: p332
}

.p333 {
  font-family: p333
}

.p334 {
  font-family: p334
}

.p335 {
  font-family: p335
}

.p336 {
  font-family: p336
}

.p337 {
  font-family: p337
}

.p338 {
  font-family: p338
}

.p339 {
  font-family: p339
}

.p340 {
  font-family: p340
}

.p341 {
  font-family: p341
}

.p342 {
  font-family: p342
}

.p343 {
  font-family: p343
}

.p344 {
  font-family: p344
}

.p345 {
  font-family: p345
}

.p346 {
  font-family: p346
}

.p347 {
  font-family: p347
}

.p348 {
  font-family: p348
}

.p349 {
  font-family: p349
}

.p350 {
  font-family: p350
}

.p351 {
  font-family: p351
}

.p352 {
  font-family: p352
}

.p353 {
  font-family: p353
}

.p354 {
  font-family: p354
}

.p355 {
  font-family: p355
}

.p356 {
  font-family: p356
}

.p357 {
  font-family: p357
}

.p358 {
  font-family: p358
}

.p359 {
  font-family: p359
}

.p360 {
  font-family: p360
}

.p361 {
  font-family: p361
}

.p362 {
  font-family: p362
}

.p363 {
  font-family: p363
}

.p364 {
  font-family: p364
}

.p365 {
  font-family: p365
}

.p366 {
  font-family: p366
}

.p367 {
  font-family: p367
}

.p368 {
  font-family: p368
}

.p369 {
  font-family: p369
}

.p370 {
  font-family: p370
}

.p371 {
  font-family: p371
}

.p372 {
  font-family: p372
}

.p373 {
  font-family: p373
}

.p374 {
  font-family: p374
}

.p375 {
  font-family: p375
}

.p376 {
  font-family: p376
}

.p377 {
  font-family: p377
}

.p378 {
  font-family: p378
}

.p379 {
  font-family: p379
}

.p380 {
  font-family: p380
}

.p381 {
  font-family: p381
}

.p382 {
  font-family: p382
}

.p383 {
  font-family: p383
}

.p384 {
  font-family: p384
}

.p385 {
  font-family: p385
}

.p386 {
  font-family: p386
}

.p387 {
  font-family: p387
}

.p388 {
  font-family: p388
}

.p389 {
  font-family: p389
}

.p390 {
  font-family: p390
}

.p391 {
  font-family: p391
}

.p392 {
  font-family: p392
}

.p393 {
  font-family: p393
}

.p394 {
  font-family: p394
}

.p395 {
  font-family: p395
}

.p396 {
  font-family: p396
}

.p397 {
  font-family: p397
}

.p398 {
  font-family: p398
}

.p399 {
  font-family: p399
}

.p400 {
  font-family: p400
}

.p401 {
  font-family: p401
}

.p402 {
  font-family: p402
}

.p403 {
  font-family: p403
}

.p404 {
  font-family: p404
}

.p405 {
  font-family: p405
}

.p406 {
  font-family: p406
}

.p407 {
  font-family: p407
}

.p408 {
  font-family: p408
}

.p409 {
  font-family: p409
}

.p410 {
  font-family: p410
}

.p411 {
  font-family: p411
}

.p412 {
  font-family: p412
}

.p413 {
  font-family: p413
}

.p414 {
  font-family: p414
}

.p415 {
  font-family: p415
}

.p416 {
  font-family: p416
}

.p417 {
  font-family: p417
}

.p418 {
  font-family: p418
}

.p419 {
  font-family: p419
}

.p420 {
  font-family: p420
}

.p421 {
  font-family: p421
}

.p422 {
  font-family: p422
}

.p423 {
  font-family: p423
}

.p424 {
  font-family: p424
}

.p425 {
  font-family: p425
}

.p426 {
  font-family: p426
}

.p427 {
  font-family: p427
}

.p428 {
  font-family: p428
}

.p429 {
  font-family: p429
}

.p430 {
  font-family: p430
}

.p431 {
  font-family: p431
}

.p432 {
  font-family: p432
}

.p433 {
  font-family: p433
}

.p434 {
  font-family: p434
}

.p435 {
  font-family: p435
}

.p436 {
  font-family: p436
}

.p437 {
  font-family: p437
}

.p438 {
  font-family: p438
}

.p439 {
  font-family: p439
}

.p440 {
  font-family: p440
}

.p441 {
  font-family: p441
}

.p442 {
  font-family: p442
}

.p443 {
  font-family: p443
}

.p444 {
  font-family: p444
}

.p445 {
  font-family: p445
}

.p446 {
  font-family: p446
}

.p447 {
  font-family: p447
}

.p448 {
  font-family: p448
}

.p449 {
  font-family: p449
}

.p450 {
  font-family: p450
}

.p451 {
  font-family: p451
}

.p452 {
  font-family: p452
}

.p453 {
  font-family: p453
}

.p454 {
  font-family: p454
}

.p455 {
  font-family: p455
}

.p456 {
  font-family: p456
}

.p457 {
  font-family: p457
}

.p458 {
  font-family: p458
}

.p459 {
  font-family: p459
}

.p460 {
  font-family: p460
}

.p461 {
  font-family: p461
}

.p462 {
  font-family: p462
}

.p463 {
  font-family: p463
}

.p464 {
  font-family: p464
}

.p465 {
  font-family: p465
}

.p466 {
  font-family: p466
}

.p467 {
  font-family: p467
}

.p468 {
  font-family: p468
}

.p469 {
  font-family: p469
}

.p470 {
  font-family: p470
}

.p471 {
  font-family: p471
}

.p472 {
  font-family: p472
}

.p473 {
  font-family: p473
}

.p474 {
  font-family: p474
}

.p475 {
  font-family: p475
}

.p476 {
  font-family: p476
}

.p477 {
  font-family: p477
}

.p478 {
  font-family: p478
}

.p479 {
  font-family: p479
}

.p480 {
  font-family: p480
}

.p481 {
  font-family: p481
}

.p482 {
  font-family: p482
}

.p483 {
  font-family: p483
}

.p484 {
  font-family: p484
}

.p485 {
  font-family: p485
}

.p486 {
  font-family: p486
}

.p487 {
  font-family: p487
}

.p488 {
  font-family: p488
}

.p489 {
  font-family: p489
}

.p490 {
  font-family: p490
}

.p491 {
  font-family: p491
}

.p492 {
  font-family: p492
}

.p493 {
  font-family: p493
}

.p494 {
  font-family: p494
}

.p495 {
  font-family: p495
}

.p496 {
  font-family: p496
}

.p497 {
  font-family: p497
}

.p498 {
  font-family: p498
}

.p499 {
  font-family: p499
}

.p500 {
  font-family: p500
}

.p501 {
  font-family: p501
}

.p502 {
  font-family: p502
}

.p503 {
  font-family: p503
}

.p504 {
  font-family: p504
}

.p505 {
  font-family: p505
}

.p506 {
  font-family: p506
}

.p507 {
  font-family: p507
}

.p508 {
  font-family: p508
}

.p509 {
  font-family: p509
}

.p510 {
  font-family: p510
}

.p511 {
  font-family: p511
}

.p512 {
  font-family: p512
}

.p513 {
  font-family: p513
}

.p514 {
  font-family: p514
}

.p515 {
  font-family: p515
}

.p516 {
  font-family: p516
}

.p517 {
  font-family: p517
}

.p518 {
  font-family: p518
}

.p519 {
  font-family: p519
}

.p520 {
  font-family: p520
}

.p521 {
  font-family: p521
}

.p522 {
  font-family: p522
}

.p523 {
  font-family: p523
}

.p524 {
  font-family: p524
}

.p525 {
  font-family: p525
}

.p526 {
  font-family: p526
}

.p527 {
  font-family: p527
}

.p528 {
  font-family: p528
}

.p529 {
  font-family: p529
}

.p530 {
  font-family: p530
}

.p531 {
  font-family: p531
}

.p532 {
  font-family: p532
}

.p533 {
  font-family: p533
}

.p534 {
  font-family: p534
}

.p535 {
  font-family: p535
}

.p536 {
  font-family: p536
}

.p537 {
  font-family: p537
}

.p538 {
  font-family: p538
}

.p539 {
  font-family: p539
}

.p540 {
  font-family: p540
}

.p541 {
  font-family: p541
}

.p542 {
  font-family: p542
}

.p543 {
  font-family: p543
}

.p544 {
  font-family: p544
}

.p545 {
  font-family: p545
}

.p546 {
  font-family: p546
}

.p547 {
  font-family: p547
}

.p548 {
  font-family: p548
}

.p549 {
  font-family: p549
}

.p550 {
  font-family: p550
}

.p551 {
  font-family: p551
}

.p552 {
  font-family: p552
}

.p553 {
  font-family: p553
}

.p554 {
  font-family: p554
}

.p555 {
  font-family: p555
}

.p556 {
  font-family: p556
}

.p557 {
  font-family: p557
}

.p558 {
  font-family: p558
}

.p559 {
  font-family: p559
}

.p560 {
  font-family: p560
}

.p561 {
  font-family: p561
}

.p562 {
  font-family: p562
}

.p563 {
  font-family: p563
}

.p564 {
  font-family: p564
}

.p565 {
  font-family: p565
}

.p566 {
  font-family: p566
}

.p567 {
  font-family: p567
}

.p568 {
  font-family: p568
}

.p569 {
  font-family: p569
}

.p570 {
  font-family: p570
}

.p571 {
  font-family: p571
}

.p572 {
  font-family: p572
}

.p573 {
  font-family: p573
}

.p574 {
  font-family: p574
}

.p575 {
  font-family: p575
}

.p576 {
  font-family: p576
}

.p577 {
  font-family: p577
}

.p578 {
  font-family: p578
}

.p579 {
  font-family: p579
}

.p580 {
  font-family: p580
}

.p581 {
  font-family: p581
}

.p582 {
  font-family: p582
}

.p583 {
  font-family: p583
}

.p584 {
  font-family: p584
}

.p585 {
  font-family: p585
}

.p586 {
  font-family: p586
}

.p587 {
  font-family: p587
}

.p588 {
  font-family: p588
}

.p589 {
  font-family: p589
}

.p590 {
  font-family: p590
}

.p591 {
  font-family: p591
}

.p592 {
  font-family: p592
}

.p593 {
  font-family: p593
}

.p594 {
  font-family: p594
}

.p595 {
  font-family: p595
}

.p596 {
  font-family: p596
}

.p597 {
  font-family: p597
}

.p598 {
  font-family: p598
}

.p599 {
  font-family: p599
}

.p600 {
  font-family: p600
}

.p601 {
  font-family: p601
}

.p602 {
  font-family: p602
}

.p603 {
  font-family: p603
}

.p604 {
  font-family: p604
}
