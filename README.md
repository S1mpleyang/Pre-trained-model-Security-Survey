# Pre-trained-model-Security-Survey

A collection of papers and resources related to security issuses of Pre-trained Models.

The organization of papers refers to our survey ["New Emerged Security and Privacy of Pre-trained Model: a Survey and Outlook"](https://arxiv.org/abs/2411.07691).

Please let us know if you find out a mistake or have any suggestions by email: meng.yang-4@student.uts.edu.au

If you find our survey useful for your research, please cite the following paper:

```
@article{yang2024new,
  title={New Emerged Security and Privacy of Pre-trained Model: a Survey and Outlook},
  author={Yang, Meng and Zhu, Tianqing and Liu, Chi and Zhou, WanLei and Yu, Shui and Yu, Philip S},
  journal={arXiv preprint arXiv:2411.07691},
  year={2024}
}
```


## Table of Contents

- [LLMSurvey](#Pre-trained-model-Security-Survey)
  - [Table of Contents](#table-of-contents)
  - [List of Pre-trained Models as Attack Target](List-of-Pre-trained-Models-as-Attack-Target)
  - [Related Sources](#related-sources)
    - [Attack](#attack)
      - [No-Change Attacks](#No-Change-Attacks)
      - [Input-Change Attacks](#Input-Change-Attacks)
      - [Model-Change Attacks](#Model-Change-Attacks)
    - [Defense](#defense)
      - [No-Change Defenses](#No-Change-Defenses)
      - [Input-Change Defenses](#Input-Change-Defenses)
      - [Model-Change Defenses](#Model-Change-Defenses)

## List of Pre-trained Models as Attack Target

### small pre-trained models
<table class="tg">
<thead>
  <tr>
    <th class="tg-0lax" align="center" rowspan="2">Model</th>
    <th class="tg-baqh" align="center" rowspan="2">Available</th>
    <th class="tg-0lax" align="center" rowspan="2">Modal</th>
    <th class="tg-baqh" align="center" rowspan="2">Size(B)</th>
    <th class="tg-0lax" align="center" rowspan="2">Base Model</th>
    <th class="tg-baqh" align="center" rowspan="2">Release Time</th>
  </tr>
  <tr>
  </tr>
  </thead>
  <tbody>
  <tr>
    <td class="tg-0lax" align="center">GPT-1</td>
    <td class="tg-baqh" align="center">Open-source</td>
    <td class="tg-0lax" align="center">text</td>
    <td class="tg-baqh" align="center">-</td>
    <td class="tg-0lax" align="center">Transformer (decoder)</td>
    <td class="tg-baqh" align="center">Jun-2018</td>
  </tr>
  <tr>
    <td class="tg-0lax" align="center">BERT</td>
    <td class="tg-baqh" align="center">Open-source</td>
    <td class="tg-0lax" align="center">text</td>
    <td class="tg-baqh" align="center">330MB</td>
    <td class="tg-0lax" align="center">Transformer (Encoder)</td>
    <td class="tg-baqh" align="center">Oct-2018</td>
  </tr>
  <tr>
    <td class="tg-0lax" align="center">CLIP</td>
    <td class="tg-baqh" align="center">Open-source</td>
    <td class="tg-0lax" align="center">multi</td>
    <td class="tg-baqh" align="center">400MB</td>
    <td class="tg-0lax" align="center">Resnet / Transformer (Encoder)</td>
    <td class="tg-baqh" align="center">Jan-2021</td>
  </tr>
  </tbody>
</table>


### large pre-trained models
<table class="tg">
<thead>
  <tr>
    <th class="tg-0lax" align="center" rowspan="2">Model</th>
    <th class="tg-baqh" align="center" rowspan="2">Available</th>
    <th class="tg-0lax" align="center" rowspan="2">Modal</th>
    <th class="tg-baqh" align="center" rowspan="2">Size(B)</th>
    <th class="tg-0lax" align="center" rowspan="2">Base Model</th>
    <th class="tg-baqh" align="center" rowspan="2">Release Time</th>
  </tr>
  <tr>
  </tr>
  </thead>
  <tbody>
   <tr>
    <td class="tg-0lax" align="center">GPT-3</td>
    <td class="tg-baqh" align="center">Close-source</td>
    <td class="tg-0lax" align="center">text</td>
    <td class="tg-baqh" align="center">6B/175B</td>
    <td class="tg-0lax" align="center">GPT-2</td>
    <td class="tg-baqh" align="center">May-2020</td>
  </tr>
  <tr>
    <td class="tg-0lax" align="center">GPT-3.5</td>
    <td class="tg-baqh" align="center">Close-source</td>
    <td class="tg-0lax" align="center">text</td>
    <td class="tg-baqh" align="center">-</td>
    <td class="tg-0lax" align="center">GPT-3</td>
    <td class="tg-baqh" align="center">Mar-2022</td>
  </tr>
  <tr>
    <td class="tg-0lax" align="center">Flamingo</td>
    <td class="tg-baqh" align="center">Close-source</td>
    <td class="tg-0lax" align="center">multi</td>
    <td class="tg-baqh" align="center">3B/9B/80B</td>
    <td class="tg-0lax" align="center">CLIP+Transformer (decoder)</td>
    <td class="tg-baqh" align="center">Apr-2022</td>
  </tr>
  </tbody>
</table>

## Related Sources

### Attack
The target model comprises two critical components: (1) the input message and (2) the model structure along with its parameters. 
Attacks can lead to changes in either or both components of the target model. Hence, this article categorizes the impacts on these model components by analyzing the changes observed before and after an attack.

![Attack Taxonomy](./images/attack.jpg)
#### No-Change Attacks

#### Input-Change Attacks

#### Model-Change Attacks


### Defense
![Defense Taxonomy](./images/defense.jpg)
#### No-Change Defenses

#### Input-Change Defenses

#### Model-Change Defenses


