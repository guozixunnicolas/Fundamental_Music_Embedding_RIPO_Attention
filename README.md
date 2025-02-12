# Fundamental Music Embedding (FME) and RIPO Attention

Code accompanying the paper 'A Domain-Knowledge-Inspired Music Embedding Space and a Novel Attention Mechanism for Symbolic Music Modeling'. [Read paper here.](https://arxiv.org/abs/2212.00973) 

Following the success of the transformer architecture in the natural language domain, transformer-like architectures have been widely applied to the domain of symbolic music recently. Symbolic music and text, however, are two different modalities. Symbolic music contains multiple attributes, both absolute attributes (e.g., pitch) and relative attributes (e.g., pitch interval). These relative attributes shape human perception of musical motifs. These important relative attributes, however, are mostly ignored in existing symbolic music modeling methods with the main reason being the lack of a musically-meaningful embedding space where both the absolute and relative embeddings of the symbolic music tokens can be efficiently represented. In this paper, we propose the Fundamental Music Embedding (FME) for symbolic music based on a bias-adjusted sinusoidal encoding within which both the absolute and the relative attributes can be embedded and the fundamental musical properties (e.g., translational invariance) are explicitly preserved. Taking advantage of the proposed FME, we further propose a novel attention mechanism based on the relative index, pitch and onset embeddings (RIPO attention) such that the musical domain knowledge can be fully utilized for symbolic music modeling. Experiment results show that our proposed model: RIPO transformer which utilizes FME and RIPO attention outperforms the state-of-the-art transformers (i.e., music transformer, linear transformer) in a melody completion task. Moreover, using the RIPO transformer in a downstream music generation task, we notice that the notorious degeneration phenomenon no longer exists and the music generated by the RIPO transformer outperforms the music generated by state-of-the-art transformer models in both subjective and objective evaluations. The code of the proposed method is available online1

## How to use

Will be added soon. 

## Citation

If you use this work please cite the following paper: 

```
@inproceedings{guo2023domain,
  title={A domain-knowledge-inspired music embedding space and a novel attention mechanism for symbolic music modeling},
  author={Guo, Zixun and Kang, Jaeyong and Herremans, Dorien},
  booktitle={Proceedings of the AAAI Conference on Artificial Intelligence},
  volume={37},
  number={4},
  pages={5070--5077},
  year={2023}
}
```
