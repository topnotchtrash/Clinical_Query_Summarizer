# Clinical_Query_Summarizer


Training data 

understanding the training data 
{
  "133": {
    "question": "how much oxazepam could cause an overdose?", // main question 
    "multi_abs_summ": "Oxazepam is used to treat anxiety and symptoms of alcohol withdrawal...", // abstractive summary generated using multiple documents
    "multi_ext_summ": "Oxazepam is a medicine used to treat anxiety and symptoms of alcohol withdrawal...", // extractive summary generated using multiple documents
    "answers": {
      "133_Answer2": {
        "answer_abs_summ": "Oxazepam is used to treat anxiety and symptoms of alcohol withdrawal...",  // abstractive summary generated using single doc, article and url //given below
        "answer_ext_summ": "Oxazepam is a medicine used to treat anxiety and symptoms of alcohol withdrawal...", // same but it's extractive summ
        "section": "What is Oxazepam overdose?: Oxazepam is a medicine...",
        "article": "Oxazepam overdose Benzodiazepine overdose Serax overdose...",
        "url": "https://www.nlm.nih.gov/medlineplus/ency/article/002516.htm",
        "rating": "3-Incomplete" // rating of the answer provided, this can be used to teach the model
      },
      "133_Answer3": {
        "answer_abs_summ": "...",
        "answer_ext_summ": "...",
        "section": "...",
        "article": "...",
        "url": "...",
        "rating": "..."
      }
    }
  }
}

shiii goes onnnnnn 

##Structure

A question
A multi-document abstractive summary
A multi-document extractive summary
Multiple single-document answers, each containing:
Abstractive summary
Extractive summary
Detailed section
Full article text
Source URL
Quality rating

