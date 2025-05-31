---
title: "调查局"
date: 2025-05-31T10:00:00+08:00
type: landing

sections:
  - block: hero
    content:
      title: "调查局档案馆📚"
      subtitle: "绝密档案解密"
      text: "黑暗中的影子"
    design:
      background:
        image:
           filename: "investigation.jpg"
        image_darken: 0.4                 # 让图片变暗以突出文字
        image_size: "cover"               # 覆盖整个区域
        image_position: "center"          # 居中显示
        text_color_light: true            # 使用白色文字
        gradient_start: '#4bb6e0'
        gradient_end: '#2563eb'
        text_color_light: true

  - block: features
    content:
      title: "主要特性"
      items:
        - name: "🔍 快速搜索"
          description: "全站内容快速搜索和定位"
        - name: "📱 移动友好"
          description: "完美的移动端阅读体验"
        - name: "✏️ 易于编辑"
          description: "支持Markdown格式编写"
        - name: "🚀 快速加载"
          description: "静态网站，访问速度极快"

  - block: markdown
    content:
      title: "开始探索"
      text: |
        ## 📖 内容分类
        
        - **专员档案** - 专员设定集
        - **人物关系** - 关系图 
        - **异能档案** - 异能谱系
        - **任务档案** - 解密调查局
        
        ---
        
        ### 准备好开始了吗？
        
        [📚 查看文档](/docs/)
        [✨ 最新文章](/posts/)
    

  - block: markdown
    id: contact
    content:
        title: "联系我们"
        text: |
          如果你有任何问题或建议，请通过以下方式联系我们：

          - **电子邮件**: qingshiyuu@gmail.com
          - **GitHub**: [github.com/QingSH-J](https://github.com/QingSH-J)
        
          - **香港 九龙塘区**
    design:
        background:
            color: "#f8f9fa"                   # 浅色背景
            text_color_light: false             # 使用深色文字
            padding: "2rem"                     # 内边距 

---