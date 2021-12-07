---
layout: post
title:  "Decomposing Block-based Visual Programming Tasks"
date:   2021-12-01 22:21:59 +00:00
image: /images/task_decomposition.png
categories: research
author: "Alperen Tercan"
venue: "In Preparation"
---
I work on using RL for program synthesis in block-based visual programming environments like Karel.
The state-of-the-art neural program synthesis methods fail for relatively complex problems(finding the mid-point of a line) which require multiple level nesting. Therefore, we developed a task decomposition framework which can automatically break any task into simpler subtasks that progressively lead to the original task. These subtasks can be used to create a curriculum for faster learning.
