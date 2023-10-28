---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        卢研究室
      image:
        filename: welcome3.png
      text: |
        <br>
        
        本研究室的研究方向主要涉及**离散数学**(组合数学)、**组合算法**、统计学中的**实验设计**、信息科学中的**编码理论**和**密码学**。特别是利用组合数学 (主要包括组合设计、代数组合学、图论、组合优化) 的工具，处理从计算机科学、信息工程等学科的实际问题中提炼出的离散数学模型、统计模型和相关计算问题。近年，我们还致力于应用**布尔表达式可满足性理论**的相关技术解决离散数学和信息科学中的具体问题。
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---