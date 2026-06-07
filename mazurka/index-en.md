---
title: Mazurka
layout: default
lang: en
---


# References

<!-- テーブルおよび2列レイアウトのデザイン（CSS） -->
<style>
  /* 2列に並べるためのコンテナ設定 */
  .mazurka-dual-layout {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    width: 100%;
    margin: 20px 0;
    font-family: 'Helvetica Neue', Arial, 'Hiragino Kaku Gothic ProN', sans-serif;
  }
  
  /* 左右それぞれのテーブルを包むボックス */
  .mazurka-column {
    flex: 1;
    min-width: 320px; /* 画面が狭くなったら自動で1列に折り返す設定 */
  }

  .mazurka-table {
    width: 100%;
    border-collapse: collapse;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.06);
    background-color: #ffffff;
  }
  
  .mazurka-table th {
    background-color: #5c4033; /* クラシックな深みのあるブラウン */
    color: #ffffff;
    text-align: left;
    padding: 10px 12px;
    font-weight: 600;
    font-size: 14px;
    letter-spacing: 0.5px;
  }
  
  .mazurka-table td {
    padding: 8px 12px; /* 縦幅を少し狭めてコンパクトに */
    border-bottom: 1px solid #eeeeee;
    color: #333333;
    font-size: 13px;
    vertical-align: middle;
  }
  
  .mazurka-table tbody tr:nth-of-type(even) {
    background-color: #f9f8f6; /* 薄いベージュの縞模様 */
  }
  
  .mazurka-table tbody tr:hover {
    background-color: #f1ede9; /* 行のホバーハイライト */
  }
  
  .mazurka-table tbody tr:last-of-type {
    border-bottom: 3px solid #5c4033;
  }
  
  .mazurka-table a {
    color: #8b5a2b;
    text-decoration: none;
    font-weight: bold;
    border-bottom: 1px dashed #8b5a2b;
    transition: all 0.2s ease;
  }
  
  .mazurka-table a:hover {
    color: #d2691e;
    border-bottom: 1px solid #d2691e;
  }

  /* スマホなど画面幅が非常に狭いときの調整 */
  @media screen and (max-width: 680px) {
    .mazurka-dual-layout {
      flex-direction: column; /* スマホでは自動的に縦並び1列に戻す */
    }
  }
</style>

<!-- ここからが2列のテーブル本体です -->
<div class="mazurka-dual-layout">

  <!-- ================= 左側：Op.6 〜 Op.41 No.4 まで ================= -->
  <div class="mazurka-column">
    <table class="mazurka-table">
      <thead>
        <tr>
          <th style="width: 30%;">Opus / Catalog No.</th>
          <th style="width: 70%;">Title</th>
        </tr>
      </thead>
      <tbody>

      <tr><td>Op. 6 No. 1</td><td><a href="https://chopinscores.org/en/partytura/47" target="_blank" rel="noopener">Mazurka No. 1 fis:</a></td></tr>
      <tr><td>Op. 6 No. 2</td><td><a href="https://chopinscores.org/en/partytura/48" target="_blank" rel="noopener">Mazurka No. 2 cis:</a></td></tr>
      <tr><td>Op. 6 No. 3</td><td><a href="https://chopinscores.org/en/partytura/49" target="_blank" rel="noopener">Mazurka No. 3 E:</a></td></tr>
      <tr><td>Op. 6 No. 4</td><td><a href="https://chopinscores.org/en/partytura/50" target="_blank" rel="noopener">Mazurka No. 4 es:</a></td></tr>
      <tr><td>Op. 7 No. 1</td><td><a href="https://chopinscores.org/en/partytura/58" target="_blank" rel="noopener">Mazurka No. 5 B:</a></td></tr>
      <tr><td>Op. 7 No. 2</td><td><a href="https://chopinscores.org/en/partytura/59" target="_blank" rel="noopener">Mazurka No. 6 a:</a></td></tr>
      <tr><td>Op. 7 No. 3</td><td><a href="https://chopinscores.org/en/partytura/60" target="_blank" rel="noopener">Mazurka No. 7 f:</a></td></tr>
      <tr><td>Op. 7 No. 4</td><td><a href="https://chopinscores.org/en/partytura/61" target="_blank" rel="noopener">Mazurka No. 8 As:</a></td></tr>
      <tr><td>Op. 7 No. 5</td><td><a href="https://chopinscores.org/en/partytura/62" target="_blank" rel="noopener">Mazurka No. 9 C:</a></td></tr>
      <tr><td>Op. 17 No. 1</td><td><a href="https://chopinscores.org/en/partytura/90" target="_blank" rel="noopener">Mazurka No. 10 B:</a></td></tr>
      <tr><td>Op. 17 No. 2</td><td><a href="https://chopinscores.org/en/partytura/91" target="_blank" rel="noopener">Mazurka No. 11 e:</a></td></tr>
      <tr><td>Op. 17 No. 3</td><td><a href="https://chopinscores.org/en/partytura/92" target="_blank" rel="noopener">Mazurka No. 12 As:</a></td></tr>
      <tr><td>Op. 17 No. 4</td><td><a href="https://chopinscores.org/en/partytura/93" target="_blank" rel="noopener">Mazurka No. 13 a:</a></td></tr>
      <tr><td>Op. 24 No. 1</td><td><a href="https://chopinscores.org/en/partytura/98" target="_blank" rel="noopener">Mazurka No. 14 g:</a></td></tr>
      <tr><td>Op. 24 No. 2</td><td><a href="https://chopinscores.org/en/partytura/99" target="_blank" rel="noopener">Mazurka No. 15 C:</a></td></tr>
      <tr><td>Op. 24 No. 3</td><td><a href="https://chopinscores.org/en/partytura/100" target="_blank" rel="noopener">Mazurka No. 16 As:</a></td></tr>
      <tr><td>Op. 24 No. 4</td><td><a href="https://chopinscores.org/en/partytura/101" target="_blank" rel="noopener">Mazurka No. 17 b:</a></td></tr>
      <tr><td>Op. 30 No. 1</td><td><a href="https://chopinscores.org/en/partytura/142" target="_blank" rel="noopener">Mazurka No. 18 c:</a></td></tr>
      <tr><td>Op. 30 No. 2</td><td><a href="https://chopinscores.org/en/partytura/143" target="_blank" rel="noopener">Mazurka No. 19 h:</a></td></tr>
      <tr><td>Op. 30 No. 3</td><td><a href="https://chopinscores.org/en/partytura/144" target="_blank" rel="noopener">Mazurka No. 20 Des:</a></td></tr>
      <tr><td>Op. 30 No. 4</td><td><a href="https://chopinscores.org/en/partytura/145" target="_blank" rel="noopener">Mazurka No. 21 cis:</a></td></tr>
      <tr><td>Op. 33 No. 1</td><td><a href="https://chopinscores.org/en/partytura/30" target="_blank" rel="noopener">Mazurka No. 22 gis:</a></td></tr>
      <tr><td>Op. 33 No. 2</td><td><a href="https://chopinscores.org/en/partytura/31" target="_blank" rel="noopener">Mazurka No. 23 D:</a></td></tr>
      <tr><td>Op. 33 No. 3</td><td><a href="https://chopinscores.org/en/partytura/32" target="_blank" rel="noopener">Mazurka No. 24 C:</a></td></tr>
      <tr><td>Op. 33 No. 4</td><td><a href="https://chopinscores.org/en/partytura/33" target="_blank" rel="noopener">Mazurka No. 25 h:</a></td></tr>
      <tr><td>Op. 41 No. 1</td><td><a href="https://chopinscores.org/en/partytura/155" target="_blank" rel="noopener">Mazurka No. 26 cis:</a></td></tr>
      <tr><td>Op. 41 No. 2</td><td><a href="https://chopinscores.org/en/partytura/156" target="_blank" rel="noopener">Mazurka No. 27 e:</a></td></tr>
      <tr><td>Op. 41 No. 3</td><td><a href="https://chopinscores.org/en/partytura/157" target="_blank" rel="noopener">Mazurka No. 28 H:</a></td></tr>
      <tr><td>Op. 41 No. 4</td><td><a href="https://chopinscores.org/en/partytura/158" target="_blank" rel="noopener">Mazurka No. 29 As:</a></td></tr>
      </tbody>
    </table>
  </div>

  <!-- ================= 右側：Op.50 〜 最後まで ================= -->
  <div class="mazurka-column">
    <table class="mazurka-table">
      <thead>
        <tr>
          <th style="width: 30%;">Opus / Catalog No.</th>
          <th style="width: 70%;">Title</th>
        </tr>
      </thead>
      <tbody>
        <tr><td>Op. 50 No. 1</td><td><a href="https://chopinscores.org/en/partytura/164" target="_blank" rel="noopener">Mazurka No. 30 G:</a></td></tr>
        <tr><td>Op. 50 No. 2</td><td><a href="https://chopinscores.org/en/partytura/165" target="_blank" rel="noopener">Mazurka No. 31 As:</a></td></tr>
        <tr><td>Op. 50 No. 3</td><td><a href="https://chopinscores.org/en/partytura/166" target="_blank" rel="noopener">Mazurka No. 32 cis:</a></td></tr>
        <tr><td>Op. 56 No. 1</td><td><a href="https://chopinscores.org/en/partytura/170" target="_blank" rel="noopener">Mazurka No. 33 H:</a></td></tr>
        <tr><td>Op. 56 No. 2</td><td><a href="https://chopinscores.org/en/partytura/171" target="_blank" rel="noopener">Mazurka No. 34 C:</a></td></tr>
        <tr><td>Op. 56 No. 3</td><td><a href="https://chopinscores.org/en/partytura/172" target="_blank" rel="noopener">Mazurka No. 35 c:</a></td></tr>
        <tr><td>Op. 59 No. 1</td><td><a href="https://chopinscores.org/en/partytura/55" target="_blank" rel="noopener">Mazurka No. 36 a:</a></td></tr>
        <tr><td>Op. 59 No. 2</td><td><a href="https://chopinscores.org/en/partytura/56" target="_blank" rel="noopener">Mazurka No. 37 As:</a></td></tr>
        <tr><td>Op. 59 No. 3</td><td><a href="https://chopinscores.org/en/partytura/57" target="_blank" rel="noopener">Mazurka No. 38 fis:</a></td></tr>
        <tr><td>Op. 63 No. 1</td><td><a href="https://chopinscores.org/en/partytura/12" target="_blank" rel="noopener">Mazurka No. 39 H:</a></td></tr>
        <tr><td>Op. 63 No. 2</td><td><a href="https://chopinscores.org/en/partytura/13" target="_blank" rel="noopener">Mazurka No. 40 f:</a></td></tr>
        <tr><td>Op. 63 No. 3</td><td><a href="https://chopinscores.org/en/partytura/14" target="_blank" rel="noopener">Mazurka No. 41 cis:</a></td></tr>
        <tr><td>Op. 67 No. 1</td><td><a href="https://chopinscores.org/en/partytura/10" target="_blank" rel="noopener">Mazurka No. 42 G: (posth.)</a></td></tr>
        <tr><td>Op. 67 No. 2</td><td><a href="https://chopinscores.org/en/partytura/11" target="_blank" rel="noopener">Mazurka No. 43 g: (posth.)</a></td></tr>
        <tr><td>Op. 67 No. 3</td><td><a href="https://chopinscores.org/en/partytura/1016" target="_blank" rel="noopener">Mazurka No. 44 C: (posth.)</a></td></tr>
        <tr><td>Op. 67 No. 4</td><td><a href="https://chopinscores.org/en/partytura/1017" target="_blank" rel="noopener">Mazurka No. 45 a: (posth.)</a></td></tr>
        <tr><td>Op. 68 No. 1</td><td><a href="https://chopinscores.org/en/partytura/1018" target="_blank" rel="noopener">Mazurka No. 46 C: (posth.)</a></td></tr>
        <tr><td>Op. 68 No. 2</td><td><a href="https://chopinscores.org/en/partytura/1019" target="_blank" rel="noopener">Mazurka No. 47 a: (posth.)</a></td></tr>
        <tr><td>Op. 68 No. 3</td><td><a href="https://chopinscores.org/en/partytura/1020" target="_blank" rel="noopener">Mazurka No. 48 F: (posth.)</a></td></tr>
        <tr><td>Op. 68 No. 4</td><td><a href="https://chopinscores.org/en/partytura/1021" target="_blank" rel="noopener">Mazurka No. 49 f: (posth.)</a></td></tr>
        
       
        <tr><td>Without Op.</td><td><a href="https://chopin.nifc.pl/en/chopin/kompozycja/9_mazurka-in-g-major" target="_blank" rel="noopener">Mazurka G: WN8 (KK IIa/2)</a></td></tr>
        <tr><td>Without Op.</td><td><a href="https://chopin.nifc.pl/en/chopin/kompozycja/8_mazurka-in-b-flat-major" target="_blank" rel="noopener">Mazurka B: WN7 (KK IIa/3)</a></td></tr>
        <tr><td>Without Op.</td><td><a href="https://ks15.imslp.org/files/imglnks/usimg/e/e2/IMSLP96715-PMLP152738-Chopin_Klindworth_Band_1_Bote_12261_B_134_scan.pdf" target="_blank" rel="noopener">Mazurka a: "Notre Temps" B134 (KK IIb/4)</a></td></tr>
        <tr><td>Without Op.</td><td><a href="https://vmirror.imslp.org/files/imglnks/usimg/4/47/IMSLP399502-PMLP152797-BnF_btv1b52500541b_1.pdf" target="_blank" rel="noopener">Mazurka a: "Émile Gaillard" B140 (KK IIb/5)</a></td></tr>
        <tr><td>Without Op.</td><td><a href="https://chopin.nifc.pl/en/chopin/kompozycja/273_mazurka-in-d-major" target="_blank" rel="noopener">Mazurka D: (KK IVa/7)</a></td></tr>
        <tr><td>Without Op.</td><td><a href="https://chopin.nifc.pl/en/chopin/kompozycja/56" target="_blank" rel="noopener">Mazurka B: B73 (KK IVb/1)</a></td></tr>
        <tr><td>Without Op.</td><td><a href="https://s9.imslp.org/files/imglnks/usimg/2/2a/IMSLP135170-PMLP199585-FChopin_Mazurka,_B.71_BH13.pdf" target="_blank" rel="noopener">Mazurka D: B71 (KK IVb/2)</a></td></tr>
        <tr><td>Without Op.</td><td><a href="https://chopin.nifc.pl/en/chopin/kompozycja/275_mazurka-in-c-major" target="_blank" rel="noopener">Mazurka C: (KK IVb/3)</a></td></tr>
        <tr><td>Without Op.</td><td><a href="https://chopin.nifc.pl/en/chopin/kompozycja/70_mazurka-in-a-flat-major-from-the-album-of-maria-szymanowska" target="_blank" rel="noopener">Mazurka As: WN45 (KK IVb/4)</a></td></tr>

      </tbody>
    </table>
  </div>

</div>


## Bibliography
* [Sapp, Craig Stuart, 2008, Hybrid Numeric/Rank Similarity Metrics for Musical Performance Analysis](https://ismir2008.ismir.net/papers/ISMIR2008_240.pdf)
