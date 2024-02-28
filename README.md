# Towards Modeling Learner Performance with Large Language Models

This repository is an implementation of our preprint "Towards Modeling Learner Performance with Large Language Models" available on [arXiv](https://arxiv.org/abs/XXXX.XXXXX).

## Authors

- Seyed Parsa Neshaei `*` ([Website](https://spneshaei.com), [Google Scholar](https://scholar.google.com/citations?user=hZFxf-kAAAAJ&hl=en), [GitHub Profile](https://github.com/spneshaei))
- Richard Davis `*` ([Website](https://people.epfl.ch/richard.davis/?lang=en), [Google Scholar](https://scholar.google.com/citations?user=kpZvywIAAAAJ&hl=en))
- Adam Hazimeh ([Website](https://people.epfl.ch/adam.hazimeh?lang=en), [GitHub Profile](https://github.com/adamhazimeh))
- Bojan Lazarevski ([Website](https://people.epfl.ch/bojan.lazarevski?lang=en), [GitHub Profile](https://github.com/bojanlazarevski1))
- Pierre Dillenbourg ([Website](https://people.epfl.ch/pierre.dillenbourg/?lang=en), [Google Scholar](https://scholar.google.com/citations?user=FdvKJcIAAAAJ&hl=en))
- Tanja Käser ([Website](https://people.epfl.ch/tanja.kaeser/?lang=en), [Google Scholar](https://scholar.google.com/citations?user=Uexe7SkAAAAJ&hl=en))

`*`: Equal contribution

*All authors are affiliated with EPFL, Lausanne, Switzerland.*

## Abstract

Recent work exploring the capabilities of pre-trained large language models (LLMs) has demonstrated their ability to act as general pattern machines by completing complex token sequences representing a wide array of tasks, including time-series prediction and robot control. This paper investigates whether the pattern recognition and sequence modeling capabilities of LLMs can be extended to the domain of knowledge tracing, a critical component in the development of intelligent tutoring systems (ITSs) that tailor educational experiences by predicting learner performance over time. In an empirical evaluation across multiple real-world datasets, we compare two approaches to using LLMs for this task, zero-shot prompting and model fine-tuning, with existing, non-LLM approaches to knowledge tracing. While LLM-based approaches do not achieve state-of-the-art performance, fine-tuned LLMs surpass the performance of naive baseline models and perform on par with standard Bayesian Knowledge Tracing approaches across multiple metrics. These findings suggest that the pattern recognition capabilities of LLMs can be used to model complex learning trajectories, opening a novel avenue for applying LLMs to educational contexts. The paper concludes with a discussion of the implications of these findings for future research, suggesting that further refinements and a deeper understanding of LLMs’ predictive mechanisms could lead to enhanced performance in knowledge tracing tasks.

## Contributing

The code supplied is intended for educational purposes, enabling the replication of our findings and encouraging continued study in this research stream. We have made our best efforts to document and validate the code prior to its release.

We have released the code for the community to use and improve; however, we do not provide any guarantees. We call for researchers to find possible issues and propose improvements.
If you discover any bugs or have ideas for new approaches, feel free to inform us.

## Citation

If you find our code, approach, or methodology useful in your research, please cite our paper:

```
@article{neshaei2024towards,
  title={Towards Modeling Learner Performance with Large Language Models},
  author={Neshaei, Seyed Parsa and Davis, Richard and Hazimeh, Adam and Lazarevski, Bojan and Dillenbourg, Pierre and K{\"a}ser, Tanja},
  journal={arXiv preprint arXiv:XXXX.XXXXX},
  year={2024}
}
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

We would like to thank the Machine Learning course (CS-433) staff at EPFL for providing the opportunity to work on this project. This project developed from an idea proposed by the authors in an ML4Science project done as a part of the course.
