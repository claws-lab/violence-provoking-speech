# (ACL 2024) A Community-Centric Perspective for Characterizing and Detecting Anti-Asian Violence-Provoking Speech 
*Paper*: [https://arxiv.org/abs/NNNN.NNNNN](https://arxiv.org/abs/NNNN.NNNNN)  
*Webpage*: [https://claws-lab.github.io/violence-provoking-speech/](https://claws-lab.github.io/violence-provoking-speech/)  
*GitHub*: [https://github.com/claws-lab/violence-provoking-speech](https://github.com/claws-lab/violence-provoking-speech/)   

*Authors*:
[Gaurav Verma](https://gaurav22verma.github.io/)<sup>1</sup>, 
[Rynaa Grover](https://www.linkedin.com/in/rynaagrover/)<sup>1</sup>, 
[Jiawei Zhou](https://jiaweizhou.me/)<sup>1</sup>, 
[Binny Mathew](https://binny-mathew.github.io/)<sup>2</sup>,
[Jordan Kraemer](https://www.linkedin.com/in/jordankraemer/)<sup>2</sup>,
[Munmun De Choudhury](http://www.munmund.net/)<sup>1</sup>,
[Srijan Kumar](https://faculty.cc.gatech.edu/~srijan/)<sup>1</sup> | *Affiliations*: <sup>1</sup>Georgia Institute of Technology, <sup>2</sup>Anti-Defamation League

# Data

## Unlabeled Data
Of the 418,999 unlabeled Twitter data that was collected for our study in Feb 2023, spanning Twitter posts from January 1, 2020 to February 1, 2023, 121,684 (about 30%) could still be accessed in August 23, 2023. We make the Twitter IDs of these posts available in the file `data/all_tweet_ids.txt`. We suspect that the fraction of posts that are still accessible will decrease over time. The potential reasons behind this could be many, including the deletion of the post by the user/Twitter, the deletion of the user's account (self-deletion of deletion/blocking by moderators), or the user transitioning to Private settings. We strongly recommend the use of provided keywords to collect new data.

## Annotated Data
We make the IDs of the Twitter posts that were identified as violence-provoking by community-crowdsourcing. Of the 246 posts that were identified as violence-provoking, 94 (about 40%) could still be accessed in August 23, 2023. The Twitter IDs of these posts is available in the file `data/violence_provoking_tweet_ids.txt`.

# Keywords
We provide the keywords used to collect the data in the file `data/keywords.py`. These keywords also include the subset from the keyword expansion strategy we adopted; please refer to Tables 6 and 7 in the paper for more details. We recommend using these keywords to collect new data.

# Bibtex
If you find these resources helpful, please cosnider citing our paper:
```bibtex
@article{verma2024community,
  title={A Community-Centric Perspective for Characterizing and Detecting Anti-Asian Violence-Provoking Speech},
  author={Verma, Gaurav and Grover, Rynaa and Zhou, Jiawei and Mathew, Binny and Kraemer, Jordan and De Choudhury, Munmun and Kumar, Srijan},
  publisher={62nd Annual Meeting of the Association for Computational Linguistics (ACL)},
  year={2024}
}
```