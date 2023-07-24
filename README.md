# Text_Retrieval

## 1. Data: 
Download here: 
<a href="https://huggingface.co/datasets/ms_marco/viewer/v1.1/test">MS MARCO</a> (Microsoft Machine Reading Comprehension Dataset)

```
Note: I am using only test data v1.1 from the MS MARCO dataset.  
```
## Dataset Structure

### Data Fields

The data fields are the same among all splits.

v1.1
*   answers: a list of string features.
*   passages: a dictionary feature containing:
    *   is_selected: a int32 feature.
    *   passage_text: a string feature.
    *   url: a string feature.
*   query: a string feature.
*   query_id: a int32 feature.
*   query_type: a string feature.
*   wellFormedAnswers: a list of string features.

## 2. Pipeline 

<img src = "https://github.com/HieuTran2019/Text_Retrieval/blob/main/Text%20Retrieval%20Pipeline.jpg" width="600" height="338" class="center">



## Reference 

<a href ="https://www.facebook.com/groups/aivietnam.edu.vn/permalink/1723045898153710/">Project: Text retrieval </a> from AI VIET NAM