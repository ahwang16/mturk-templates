# MTurk Templates for Complex Human Evaluation Tasks
A collection of complex Amazon Mechanical Turk templates I created for my work. These templates are designed to make complex annotations tasks easier for human annotators to evaluate by breaking down each HIT into several subtasks. I will add templates and references here as I work on them.

## Compare Recipes
This MTurk Task asks Turkers to compare two recipes by displaying the entirety of one and providing the other one step at a time. The ingredients list is shown to the far left to help ground the task in background information. Turkers answer questions about each step of the second recipe, followed by questions about both recipes in general. This template could be adapted for any task that involves comparing two long texts, like summarization, style transfer, machine translation, or question answering.

<p align="center">
  <img src="https://github.com/ahwang16/mturk-templates/blob/master/_images/compare_recipes.gif" alt="MTurk interface for the Compare Recipes task" title="Compare Recipes HIT"> 
</p>

Used in [Large Language Models as Sous Chefs: Revising Recipes with GPT-3](https://arxiv.org/abs/2306.13986) (Hwang et al., 2023).

## Use and Citation
Feel free to fork this repository, submit pull requests, or use these templates for your work. If you use any of these templates for your work or inspiration, please cite this repository:

```
@software{Hwang_MTurk_Templates_for_2023,
  author = {Hwang, Alyssa},
  month = jun,
  title = {{MTurk Templates for Complex Human Evaluation Tasks}},
  url = {https://github.com/ahwang16/mturk-templates},
  version = {1.0.0},
  year = {2023}
}
```
