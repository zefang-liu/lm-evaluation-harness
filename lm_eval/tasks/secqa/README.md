# SecQA

### Paper

Title: `SecQA: A Concise Question-Answering Dataset for Evaluating Large Language Models in Computer Security`

Abstract: https://arxiv.org/abs/2312.15838

SecQA is a concise, two-version dataset designed to evaluate and benchmark various LLMs in understanding computer security principles through multiple-choice questions derived from a textbook.

Homepage: https://huggingface.co/datasets/zefang-liu/secqa


### Citation

```
@misc{liu2023secqa,
      title={SecQA: A Concise Question-Answering Dataset for Evaluating Large Language Models in Computer Security}, 
      author={Zefang Liu},
      year={2023},
      eprint={2312.15838},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```

### Tasks

* `secqa_v1_generative`: SecQA v1 text generation task
* `secqa_v2_generative`: SecQA v2 text generation task

### Checklist

For adding novel benchmarks/datasets to the library:
* [X] Is the task an existing benchmark in the literature?
  * [X] Have you referenced the original paper that introduced the task?
  * [X] If yes, does the original paper provide a reference implementation? If so, have you checked against the reference implementation and documented how to run such a test?


If other tasks on this dataset are already supported:
* [ ] Is the "Main" variant of this task clearly denoted?
* [ ] Have you provided a short sentence in a README on what each new variant adds / evaluates?
* [ ] Have you noted which, if any, published evaluation setups are matched by this variant?
