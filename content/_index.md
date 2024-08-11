---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        مجلة
        التميز المؤسسي
      image:
        filename: welcome.jpg
      text: |
        <br>        
         نتطلع ان نكون المجلة الأولى التي يعتمد عليها المديرون والمهتمون بمجال الإدارة، من خلال تقديم محتوى متنوع وموثوق يتناول أحدث الاتجاهات، الأساليب، والتقنيات في عالم الإدارة.
         نسعى جاهدين لتزويد قرائنا بالأدوات والمعرفة اللازمة لتعزيز قدراتهم الإدارية..
  
  - block: collection
    content:
      title: اخر المقالات
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

  - block: collection
    content:
      title: اخر اصداراتنا
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="فريق النشر →" %}}
    design:
      columns: '1'
---
