---
layout: default
---


**Instructor**: Jack Morris

**Meetings**: MONDAY 5:55pm-7:10pm (Bloomberg 091)

**Office hours**: By appointment only (for now)

[Canvas Link](https://canvas.cornell.edu/courses/63269)

## Course description

Students will learn deep neural network fundamentals and practical skills for training and evaluating these networks. We will practice using a variety of tools in real-world scenarios to prepare students for practical deep learning problems seen in both research and industry.


## Schedule

### Lecture

<table>
    <thead>
    <tr>
      <th style="text-align: left">Week</th>
      <th style="text-align: left">Date</th>
      <th style="text-align: left">Title</th>
      <th style="text-align: left">Slides</th>
      <th style="text-align: left">Puzzle</th>
    </tr>
  </thead>
<tbody>
{% assign sorted_weeks = site.posts | sort: 'index' %}

{% for week in sorted_weeks %}
    <tr>
        <td> {{ week.index }} </td>
        <td> {{ week.day }} </td>
        <td> {{ week.title }} </td>
        {% if week.slides %}
            <td> <a href="{{ site.baseurl }}{{ week.slides }}"> 📊 </a> </td>
        {% else %}
            <td> </td>
        {% endif %}
        {% if week.puzzle %}
            <td> <a href="{{ week.puzzle }}"> 🧩 </a> </td>
        {% else %}
            <td> </td>
        {% endif %}
    </tr>
    {% endfor %}
</tbody>
</table>


## Project

All students will complete a small project at the end of the semester to test their new deep learning skills. The goal is to build something that uses contemporary technology to do something interesting and exciting and to showcase your skills as an engineer.

<a href="/project">For more information on the project, see the Project page.</a>

### Project working sessions

| Date        |           | |
|:-------------|:------------------|:------|
| 3/25           |  |   |
| 4/8           |  |   |
| 4/15           |  |   |
| 4/22           |  |   |

### Resources

- [Recipe for Training Neural Networks](https://karpathy.github.io/2019/04/25/recipe/) - Andrej Karpathy
- [Frequently Asked Questions](https://pytorch.org/docs/stable/notes/faq.html) – PyTorch Team (actually a very good resource for beginners!!)
- [GPT in 60 Lines of NumPy](https://jaykmody.com/blog/gpt-from-scratch/)
- [Intro to Text Embeddings (Stack Overflow)](https://stackoverflow.blog/2023/11/09/an-intuitive-introduction-to-text-embeddings/) - a decent introduction to text embeddings
