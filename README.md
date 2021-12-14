# illness-dataset
This is the extended version of the dataset introduced in the following paper: <br/>
*Contextual Multi-View Query Learning for Short Text Classification in User-Generated Data*, Payam Karisani, Negin Karisani, and Li Xiong. Preprint 2021. [Link](https://arxiv.org/abs/2112.02611)

**Dataset Description** <br/>
See the paper for details, but in short: the dataset consists of 22,660 documents (tweets) collected in 2018 and 2019. It spans across four domains: Alzheimer's, Parkinson's, Cancer, and Diabetes. You can see the stats below. <br/>

| Domain | Doc # | Negative | Positive |
| ------ | ----- | -------- | -------- |
| Alzheimer's | 4,023 | 3,380 | 643 |
| Parkinson's | 6,216 | 5,221 | 995 |
| Cancer | 6,006 | 4,780 | 1,226 |
| Diabetes | 6,415 | 5,339 | 1,076 |
| **Total** | _22,660_ | _18,720_ | _3,940_ |

A document in this dataset is labeled positive, if it mentions a person(s) diagnosed with the disease.<br/><br/>

**Dataset Format** <br/>
The file is tab separated:
1) Domain name
2) Label (0 and 1 indicate negative. 2 and 3 indicate positive)
3) Document body
<br/><br/>

If you are using this dataset, please cite the paper below:

```
@misc{karisani2021contextual,
      title={Contextual Multi-View Query Learning for Short Text Classification in User-Generated Data}, 
      author={Payam Karisani and Negin Karisani and Li Xiong},
      year={2021},
      eprint={2112.02611},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```
