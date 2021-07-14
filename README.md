# CRS-Paper-List
In this repository, we summary a paper list of works in conversational recommendation system and its related areas.


- Contributed by **[Victor Li Chuang](github.com/xiaowudeshen)** and collaboration is welcome for anyone interested in this repo.

Please follow [this link](./README_by_year.md) to view papers in chronological order. 

## [Content](#content)

<table>
<tr><td colspan="2"><a href="#survey-papers">1. Survey</a></td></tr> 
<tr><td colspan="2"><a href="#models">2. Models</a></td></tr>
<tr>
    <td>&emsp;<a href="#basic-seq2seq-models">2.1 Basic Seq2Seq Models</a></td>
    <td>&ensp;<a href="#encoding-answers">2.2 Encoding Answers</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#linguistic-features">2.3 Linguistic Features</a></td>
    <td>&ensp;<a href="#question-specific-rewards">2.4 Question-specific Rewards</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#content-selection">2.5 Content Selection</a></td>
    <td>&ensp;<a href="#question-type-modeling">2.6 Question Type Modeling</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#encode-wider-contexts">2.7 Encode wider contexts</a></td>
    <td>&ensp;<a href="#qg-with-pretraining">2.8 QG with pretraining</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#other-directions">2.9 Other Directions</a></td>
</tr>
<tr><td colspan="2"><a href="#applications">2. Applications</a></td></tr> 
<tr>
    <td>&emsp;<a href="#difficulty-controllable-QG">2.1 Difficulty Controllable QG</a></td>
    <td>&ensp;<a href="#conversational-QG">2.2 Conversational QG</a></td>
</tr> 
<tr>
    <td>&emsp;<a href="#asking-deep-questions">2.3 Asking Deep Questions</a></td>
    <td>&ensp;<a href="#combining-QA-and-QG">2.4 Combining QA and QG</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#QG-from-knowledge-graphs">2.5 QG from knowledge graphs</a></td>
    <td>&ensp;<a href="#visual-question-generation">2.6 Visual Question Generation</a></td>
</tr> 
<tr>
    <td>&emsp;<a href="#distractor-generation">2.7 Distractor Generation</a></td>
    <td>&ensp;<a href="#cross-lingual-QG">2.8 Cross-lingual QG</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#clarification-question-generation">2.9 Clarification Question Generation</a></td>
</tr>
<tr><td colspan="2"><a href="#evaluation">3. Evaluation</a></td></tr>
<tr><td colspan="2"><a href="#resources">4. Resources</a></td></tr>
</table>

## [Survey papers](#content)
1. **Recent Advances in Neural Question Generation.** arxiv, 2019. [paper](https://arxiv.org/pdf/1905.08949.pdf)
    
    *Liangming Pan, Wenqiang Lei, Tat-Seng Chua, Min-Yen Kan* 

2. **A Systematic Review of Automatic Question Generation for Educational Purposes.** International Journal of Artificial Intelligence in Education, 2020. [paper](https://link.springer.com/content/pdf/10.1007/s40593-019-00186-y.pdf)
    
    *Ghader Kurdi, Jared Leo, Bijan Parsia, Uli Sattler, Salam Al-Emari* 

## [Models](#content)   

### [Basic Seq2Seq Models](#basic-models)

Basic Seq2Seq models with attention to generate questions. 

1. **Learning to ask: Neural question generation for reading comprehension.** ACL, 2017. [paper](https://www.aclweb.org/anthology/P17-1123.pdf)

    *Xinya Du, Junru Shao, Claire Cardie.*
