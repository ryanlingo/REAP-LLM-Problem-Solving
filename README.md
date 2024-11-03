# REAP-LLM-Problem-Solving

## Enhancing LLM Problem Solving with REAP: Reflection, Explicit Problem Deconstruction, and Advanced Prompting

This repository contains resources and materials for the research paper: **"[Enhancing LLM Problem Solving with REAP: Reflection, Explicit Problem Deconstruction, and Advanced Prompting](https://arxiv.org/abs/2409.09415)"**. The REAP framework improves problem-solving capabilities in large language models (LLMs) by guiding them through structured, context-aware reasoning processes, enhancing logical consistency and clarity.

## Repository Contents

- **README.md**: Overview of the repository and instructions for usage.
- **REAP_Prompt.md**: The detailed REAP prompt framework for structured problem-solving.
- **data/**: Contains the questions from the linguistic benchmark dataset used in the study. This dataset originates from [Easy Problems That LLMs Get Wrong](https://arxiv.org/abs/2405.19616). Please cite this paper if you use these questions.

## Usage

To use the REAP prompt:

1. Insert your problem into the REAP prompt at the end in the section labeled `<PROBLEM>`.
2. Run the REAP prompt on any of your available large language models (LLMs) to guide the model through structured problem-solving steps.

If you would like to try REAP on the problems we used in our benchmark, the questions are available in the `data/` folder. These questions are sourced from [Easy Problems That LLMs Get Wrong](https://arxiv.org/abs/2405.19616). Please make sure to cite this paper if you use this dataset.

## Citing This Work

If you use this REAP framework in your research, please cite our paper:

```bibtex
@article{lingo2024REAP,
  title={Enhancing LLM Problem Solving with REAP: Reflection, Explicit Problem Deconstruction, and Advanced Prompting},
  author={Lingo, Ryan and Arroyo, Martin and Chhajer, Rajeev},
  journal={arXiv preprint arXiv:2409.09415},
  year={2024},
  url={https://arxiv.org/abs/2409.09415}
}
```

For any questions used from the `data/` folder, please also cite:

```bibtex
@article{williams2024EasyProblems,
  title={Easy Problems That LLMs Get Wrong},
  author={Williams, S and Huckle, J},
  journal={arXiv preprint arXiv:2405.19616},
  year={2024},
  url={https://arxiv.org/abs/2405.19616}
}
```

## License

This repository is licensed under the **Creative Commons Zero v1.0 Universal (CC0)** license, dedicating the work to the public domain. See the LICENSE file for details.
