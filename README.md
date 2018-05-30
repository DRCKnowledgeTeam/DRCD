# Delta Reading Comprehension Dataset 
台達閱讀理解資料集 Delta Reading Comprehension Dataset (DRCD) 屬於通用領域繁體中文機器閱讀理解資料集。
本資料集期望成為適用於遷移學習之標準中文閱讀理解資料集。
本資料集從2,108篇維基條目中整理出10,014篇段落，並從段落中標註出30,000多個問題
關於資料集之更詳細資訊請洽詢論文：
For more information please refer to Paper https://arxiv.org/abs/

## Copyright Notice 版權聲明

本資料集整理、改編自維基百科，其內容以CC-BY-SA 3.0條款發布。
台達電子對於本資料集內容之正確性不為任何擔保，且不就因使用或倚賴本資料集而引致的任何損失，承擔任何責任。
CC-BY-SA 3.0相關條款請參考以下連結
http://creativecommons.org/licenses/by-sa/3.0/


## Data format 資料格式

- version : <String> 資料集版本
- Data : <Array>
  - title : <String> : 文章標題
  - id : <String> : 文章編號
  - paragraphs : <Array>
    - id : <String> : 文章編號_段落編號
    - context : <String> : 段落內容
    - qas : <Array>
      - question : <String> : 問題內容
      - id :<String> : 文章編號_段落編號_問題編號
      - answers : <Arrays>
        - answer_start : <int> text在文中位置
        - id : <String> : "1"表示為人工標註的答案，"2"以上為人工答題的答案
        - text : <string> : 答案內容

## Contact us 聯繫我們 

- 資料所有： <a href="http://www.deltaww.com/about/innovation_ch.aspx?secID=5&amp;pid=4&amp;tid=0&amp;hl=zh-TW">台達研究院Delta Research Center</a>
- Email: <a href="mailto:cchieh.shao@deltaww.com">cchieh.shao@deltaww.com</a>