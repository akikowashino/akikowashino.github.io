---
title: Mazurka
layout: default
lang: en
---


# 参考資料

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
          <th style="width: 30%;">作品番号</th>
          <th style="width: 70%;">曲名</th>
        </tr>
      </thead>
      <tbody>

<tr><td>Op. 6 No. 1</td><td><a href="https://chopinscores.org/en/partytura/47" target="_blank" rel="noopener">マズルカ 第1番 嬰ヘ短調</a></td></tr>
      <tr><td>Op. 6 No. 2</td><td><a href="https://chopinscores.org/en/partytura/48" target="_blank" rel="noopener">マズルカ 第2番 嬰ハ短調</a></td></tr>
      <tr><td>Op. 6 No. 3</td><td><a href="https://chopinscores.org/en/partytura/49" target="_blank" rel="noopener">マズルカ 第3番 ホ長調</a></td></tr>
      <tr><td>Op. 6 No. 4</td><td><a href="https://chopinscores.org/en/partytura/50" target="_blank" rel="noopener">マズルカ 第4番 変ホ短調</a></td></tr>
        <tr><td>Op. 7 No. 1</td><td><a href="https://chopinscores.org/en/partytura/58" target="_blank" rel="noopener">マズルカ 第5番 変ロ長調</a></td></tr>
        <tr><td>Op. 7 No. 2</td><td><a href="https://chopinscores.org/en/partytura/59" target="_blank" rel="noopener">マズルカ 第6番 イ短調</a></td></tr>
        <tr><td>Op. 7 No. 3</td><td><a href="https://chopinscores.org/en/partytura/60" target="_blank" rel="noopener">マズルカ 第7番 ヘ短調</a></td></tr>
        <tr><td>Op. 7 No. 4</td><td><a href="https://chopinscores.org/en/partytura/61" target="_blank" rel="noopener">マズルカ 第8番 変イ長調</a></td></tr>
        <tr><td>Op. 7 No. 5</td><td><a href="https://chopinscores.org/en/partytura/62" target="_blank" rel="noopener">マズルカ 第9番 ハ長調</a></td></tr>
        <tr><td>Op. 17 No. 1</td><td><a href="https://chopinscores.org/en/partytura/90" target="_blank" rel="noopener">マズルカ 第10番 変ロ長調</a></td></tr>
        <tr><td>Op. 17 No. 2</td><td><a href="https://chopinscores.org/en/partytura/91" target="_blank" rel="noopener">マズルカ 第11番 ホ短調</a></td></tr>
        <tr><td>Op. 17 No. 3</td><td><a href="https://chopinscores.org/en/partytura/92" target="_blank" rel="noopener">マズルカ 第12番 変イ長調</a></td></tr>
        <tr><td>Op. 17 No. 4</td><td><a href="https://chopinscores.org/en/partytura/93" target="_blank" rel="noopener">マズルカ 第13番 イ短調</a></td></tr>
        <tr><td>Op. 24 No. 1</td><td><a href="https://chopinscores.org/en/partytura/98" target="_blank" rel="noopener">マズルカ 第14番 ト短調</a></td></tr>
        <tr><td>Op. 24 No. 2</td><td><a href="https://chopinscores.org/en/partytura/99" target="_blank" rel="noopener">マズルカ 第15番 ハ長調</a></td></tr>
        <tr><td>Op. 24 No. 3</td><td><a href="https://chopinscores.org/en/partytura/100" target="_blank" rel="noopener">マズルカ 第16番 変イ長調</a></td></tr>
        <tr><td>Op. 24 No. 4</td><td><a href="https://chopinscores.org/en/partytura/101" target="_blank" rel="noopener">マズルカ 第17番 変ロ短調</a></td></tr>
        <tr><td>Op. 30 No. 1</td><td><a href="https://chopinscores.org/en/partytura/142" target="_blank" rel="noopener">マズルカ 第18番 ハ短調</a></td></tr>
        <tr><td>Op. 30 No. 2</td><td><a href="https://chopinscores.org/en/partytura/143" target="_blank" rel="noopener">マズルカ 第19番 ロ短調</a></td></tr>
        <tr><td>Op. 30 No. 3</td><td><a href="https://chopinscores.org/en/partytura/144" target="_blank" rel="noopener">マズルカ 第20番 変ニ長調</a></td></tr>
        <tr><td>Op. 30 No. 4</td><td><a href="https://chopinscores.org/en/partytura/145" target="_blank" rel="noopener">マズルカ 第21番 嬰ハ短調</a></td></tr>
        <tr><td>Op. 33 No. 1</td><td><a href="https://chopinscores.org/en/partytura/30" target="_blank" rel="noopener">マズルカ 第22番 嬰ト短調</a></td></tr>
        <tr><td>Op. 33 No. 2</td><td><a href="https://chopinscores.org/en/partytura/31" target="_blank" rel="noopener">マズルカ 第23番 ニ長調</a></td></tr>
        <tr><td>Op. 33 No. 3</td><td><a href="https://chopinscores.org/en/partytura/32" target="_blank" rel="noopener">マズルカ 第24番 ハ長調</a></td></tr>
        <tr><td>Op. 33 No. 4</td><td><a href="https://chopinscores.org/en/partytura/33" target="_blank" rel="noopener">マズルカ 第25番 ロ短調</a></td></tr>
        <tr><td>Op. 41 No. 1</td><td><a href="https://chopinscores.org/en/partytura/155" target="_blank" rel="noopener">マズルカ 第26番 嬰ハ短調</a></td></tr>
        <tr><td>Op. 41 No. 2</td><td><a href="https://chopinscores.org/en/partytura/156" target="_blank" rel="noopener">マズルカ 第27番 ホ短調</a></td></tr>
        <tr><td>Op. 41 No. 3</td><td><a href="https://chopinscores.org/en/partytura/157" target="_blank" rel="noopener">マズルカ 第28番 ロ長調</a></td></tr>
        <tr><td>Op. 41 No. 4</td><td><a href="https://chopinscores.org/en/partytura/158" target="_blank" rel="noopener">マズルカ 第29番 変イ長調</a></td></tr>
      </tbody>
    </table>
  </div>

  <!-- ================= 右側：Op.50 〜 最後まで ================= -->
  <div class="mazurka-column">
    <table class="mazurka-table">
      <thead>
        <tr>
          <th style="width: 30%;">作品番号</th>
          <th style="width: 70%;">曲名</th>
        </tr>
      </thead>
      <tbody>
        <tr><td>Op. 50 No. 1</td><td><a href="https://chopinscores.org/en/partytura/164" target="_blank" rel="noopener">マズルカ 第30番 ト長調</a></td></tr>
        <tr><td>Op. 50 No. 2</td><td><a href="https://chopinscores.org/en/partytura/165" target="_blank" rel="noopener">マズルカ 第31番 変イ長調</a></td></tr>
        <tr><td>Op. 50 No. 3</td><td><a href="https://chopinscores.org/en/partytura/166" target="_blank" rel="noopener">マズルカ 第32番 嬰ハ短調</a></td></tr>
        <tr><td>Op. 56 No. 1</td><td><a href="https://chopinscores.org/en/partytura/170" target="_blank" rel="noopener">マズルカ 第33番 ロ長調</a></td></tr>
        <tr><td>Op. 56 No. 2</td><td><a href="https://chopinscores.org/en/partytura/171" target="_blank" rel="noopener">マズルカ 第34番 ハ長調</a></td></tr>
        <tr><td>Op. 56 No. 3</td><td><a href="https://chopinscores.org/en/partytura/172" target="_blank" rel="noopener">マズルカ 第35番 ハ短調</a></td></tr>
        <tr><td>Op. 59 No. 1</td><td><a href="https://chopinscores.org/en/partytura/55" target="_blank" rel="noopener">マズルカ 第36番 イ短調</a></td></tr>
        <tr><td>Op. 59 No. 2</td><td><a href="https://chopinscores.org/en/partytura/56" target="_blank" rel="noopener">マズルカ 第37番 変イ長調</a></td></tr>
        <tr><td>Op. 59 No. 3</td><td><a href="https://chopinscores.org/en/partytura/57" target="_blank" rel="noopener">マズルカ 第38番 嬰ヘ短調</a></td></tr>
        <tr><td>Op. 63 No. 1</td><td><a href="#" target="_blank" rel="noopener">マズルカ 第39番 ロ長調</a></td></tr>
        <tr><td>Op. 63 No. 2</td><td><a href="#" target="_blank" rel="noopener">マズルカ 第40番 ヘ短調</a></td></tr>
        <tr><td>Op. 63 No. 3</td><td><a href="#" target="_blank" rel="noopener">マズルカ 第41番 嬰ハ短調</a></td></tr>
        <tr><td>Op. 67 No. 1</td><td><a href="#" target="_blank" rel="noopener">マズルカ 第42番 ト長調 (遺作)</a></td></tr>
        <tr><td>Op. 67 No. 2</td><td><a href="#" target="_blank" rel="noopener">マズルカ 第43番 ト短調 (遺作)</a></td></tr>
        <tr><td>Op. 67 No. 3</td><td><a href="#" target="_blank" rel="noopener">マズルカ 第44番 ハ長調 (遺作)</a></td></tr>
        <tr><td>Op. 67 No. 4</td><td><a href="#" target="_blank" rel="noopener">マズルカ 第45番 イ短調 (遺作)</a></td></tr>
        <tr><td>Op. 68 No. 1</td><td><a href="#" target="_blank" rel="noopener">マズルカ 第46番 ハ長調 (遺作)</a></td></tr>
        <tr><td>Op. 68 No. 2</td><td><a href="#" target="_blank" rel="noopener">マズルカ 第47番 イ短調 (遺作)</a></td></tr>
        <tr><td>Op. 68 No. 3</td><td><a href="#" target="_blank" rel="noopener">マズルカ 第48番 ヘ長調 (遺作)</a></td></tr>
        <tr><td>Op. 68 No. 4</td><td><a href="#" target="_blank" rel="noopener">マズルカ 第49番 ヘ短調 (遺作)</a></td></tr>
        <tr><td>作品番号なし</td><td><a href="#" target="_blank" rel="noopener">マズルカ 第50番 イ短調「ノートル・タン」</a></td></tr>
        <tr><td>作品番号なし</td><td><a href="#" target="_blank" rel="noopener">マズルカ 第51番 イ短調「エミール・ガイヤール」</a></td></tr>
        <tr><td>作品番号なし</td><td><a href="#" target="_blank" rel="noopener">マズルカ 変ロ長調</a></td></tr>
        <tr><td>作品番号なし</td><td><a href="#" target="_blank" rel="noopener">マズルカ ト長調</a></td></tr>
        <tr><td>作品番号なし</td><td><a href="#" target="_blank" rel="noopener">マズルカ ニ長調</a></td></tr>
        <tr><td>作品番号なし</td><td><a href="#" target="_blank" rel="noopener">マズルカ ニ長調</a></td></tr>
        <tr><td>作品番号なし</td><td><a href="#" target="_blank" rel="noopener">マズルカ 変ロ長調</a></td></tr>
        <tr><td>作品番号なし</td><td><a href="#" target="_blank" rel="noopener">マズルカ ハ長調</a></td></tr>
        <tr><td>作品番号なし</td><td><a href="#" target="_blank" rel="noopener">マズルカ 変イ長調</a></td></tr>
        <tr><td>作品番号なし</td><td><a href="#" target="_blank" rel="noopener">マズルカ 変ロ長調</a></td></tr>
      </tbody>
    </table>
  </div>

</div>





## 参考文献

https://ismir2008.ismir.net/papers/ISMIR2008_240.pdf

