# Comprehensive-Segmentation-of-Type-A-Aortic-Dissection-with-Clinically-oriented-Evaluation

Type A aortic dissection (TAAD) is a cardiac emergency in which rapid diagnosis,
prognosis prediction, and surgical planning are critical for patient survival. A comprehensive understanding of the anatomic structures and related features of TAAD patients
is the key to completing these tasks. However, due to the emergent nature of this disease
and requirement of advanced expertise, manual segmentation of these anatomic structures is not routinely available in clinical practice. Currently, automatic segmentation
of TAAD is a focus of the cardiovascular imaging research. However, existing works
have two limitations: no comprehensive public dataset and lack of clinically-oriented
evaluation. To address these limitations, in this paper we propose imageTAAD, the first
comprehensive segmentation dataset of TAAD with clinically-oriented evaluation. The
dataset is comprised of 120 cases, and each case is annotated by medical experts with
35 foreground classes reflecting the clinical needs for diagnosis, prognosis prediction
and surgical planning for TAAD. In addition, we have identified four key clinical features for clinically-oriented evaluation. We also propose SegTAAD, a baseline method
for comprehensive segmentation of TAAD. SegTAAD utilizes two pieces of domain
knowledge: (1) the boundaries play a key role in the evaluation of clinical features, and
can enhance the segmentation performance, and (2) the tear locates between TL and FL.
We have conducted intensive experiments with a variety of state-of-the-art methods, and
experimental results have shown that our method achieves state-of-the-art performance
on the ImageTAAD dataset in terms of overall DSC score, 95% Hausdorff distance, and
four clinical features. In our study, we also found an interesting phenomenon that a
higher DSC score does not necessarily indicate better accuracy in clinical feature extraction. Our code and dataset will also be publish to facilitate further research in this
important and challenging task along with this paper.

Please send emails to me xiao.wei.xu@foxmail.com for the link and the password to download the dataset and the benchmark.
Currently we are still preparing the final version of the published dataset and code.
