---
layout: page       # 必须和主题 _layouts/page.html 匹配，确保 Markdown 被渲染
title: 关于
permalink: /about/ # 和导航栏「关于」的 href 一致
---

<!-- 外层猫猫主题容器：保留所有萌化装饰，不干扰 Markdown 渲染 -->
<div style="position:relative; padding:30px; margin:20px auto; max-width: 800px; 
            background:linear-gradient(135deg,#fff0f5,#e6e6fa); 
            border-radius:20px; box-shadow:0 10px 30px rgba(255,105,180,0.2); 
            overflow:hidden;">

  <!-- 猫耳装饰（绝对定位，不影响内容流） -->
  <div style="position:absolute; top:-30px; left:50%; transform:translateX(-50%); display:flex; gap:80px;">
    <div style="width:40px; height:60px; background:#ffb6c1; clip-path:polygon(50% 0%,0% 100%,100% 100%);"></div>
    <div style="width:40px; height:60px; background:#ffb6c1; clip-path:polygon(50% 0%,0% 100%,100% 100%);"></div>
  </div>

  <!-- 头像+标题（纯 HTML，避免 Markdown 干扰） -->
  <div style="text-align:center; margin-bottom:30px;">
    <div style="width:120px; height:120px; border-radius:50%; background:linear-gradient(45deg,#ffb6c1,#e6e6fa); 
                margin:0 auto 15px; display:flex; align-items:center; justify-content:center; 
                font-size:50px; color:white; border:4px solid white; box-shadow:0 5px 15px rgba(0,0,0,0.1);">🐱</div>
    <h1 style="font-size:2rem; color:#ff69b4;">成霜喵喵</h1>
    <p style="font-size:1.2rem; color:#ff1493;">高考奋斗中の成霜喵喵🐾</p>
  </div>

  <!-- 核心内容：用 <article class="markdown-body"> 包裹，强制主题解析 Markdown -->
  <article class="markdown-body" style="background:transparent; padding:0;">

    ### 🐾关于我🐾  
    😸是成霜喵喵，在为高考而奋斗喵～  
    也许眼前充满苟且，但学习是为了 **诗和远方** 🐾。  

    本站于 **2025年6月19日** 正式上线，记录技术思考与生活点滴~  

    > "每一天都要像猫咪追逐阳光一样追逐知识喵！✨"  
    > —— 成霜喵喵的学习信条  


    ### 🌸 个人特质  
    <span style="background:rgba(255,182,193,0.2); padding:5px 10px; border-radius:10px; margin:3px; display:inline-block;">学习型猫猫</span>  
    <span style="background:rgba(255,182,193,0.2); padding:5px 10px; border-radius:10px; margin:3px; display:inline-block;">技术爱好者</span>  
    <span style="background:rgba(255,182,193,0.2); padding:5px 10px; border-radius:10px; margin:3px; display:inline-block;">软萌爱好者</span>  
    <span style="background:rgba(255,182,193,0.2); padding:5px 10px; border-radius:10px; margin:3px; display:inline-block;">猫耳收藏家</span>  
    <span style="background:rgba(255,182,193,0.2); padding:5px 10px; border-radius:10px; margin:3px; display:inline-block;">2305班信息委员</span>  


    ### 📮 联系成霜喵喵  

    <div style="display:grid; grid-template-columns:repeat(auto-fit,minmax(200px,1fr)); gap:15px; margin-top:20px;">
      <div style="background:rgba(255,182,193,0.1); border:2px dashed #ffb6c1; border-radius:15px; padding:15px; text-align:center;">
        <span style="font-size:24px; color:#ff69b4;">🐾</span>  
        **GitHub**  
        [@YLCS-MM](https://github.com/YLCS-MM){:target="_blank"}
      </div>
      <div style="background:rgba(255,182,193,0.1); border:2px dashed #ffb6c1; border-radius:15px; padding:15px; text-align:center;">
        <span style="font-size:24px; color:#ff69b4;">✉️</span>  
        **邮箱**  
        [15873505918@163.com](mailto:15873505918@163.com)
      </div>
    </div>

  </article>

  <!-- 漂浮猫爪动画（不影响内容排版） -->
  <span class="float-paw" style="position:absolute; top:20%; left:15%; font-size:24px;">🐾</span>
  <span class="float-paw" style="position:absolute; top:30%; right:20%; font-size:24px;">🐾</span>
  <span class="float-paw" style="position:absolute; bottom:25%; left:25%; font-size:24px;">🐾</span>

  <!-- 猫尾巴装饰（绝对定位，不影响内容流） -->
  <div style="position:absolute; bottom:-100px; right:-30px; width:150px; height:250px; background:#ffb6c1; 
              border-radius:50% 0 0 50%; transform:rotate(45deg); opacity:0.3; z-index:-1;"></div>

  <!-- 动画样式：局部作用，不污染全局 -->
  <style>
    @keyframes float {
      0% { transform: translateY(0); }
      50% { transform: translateY(-8px); }
      100% { transform: translateY(0); }
    }
    .float-paw {
      display: inline-block;
      animation: float 3s infinite ease-in-out;
    }
    .float-paw:nth-child(1) { animation-delay: 0s; }
    .float-paw:nth-child(2) { animation-delay: 1s; }
    .float-paw:nth-child(3) { animation-delay: 2s; }
  </style>
</div>
