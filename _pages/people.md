---
title: 师资力量
author_profile: false
re: true
---

<div class="profile-row">
  <div class="profile-card">
    <a href="{{ '_pages/teacher/guozhongwen/' | relative_url }}">
      <img src="{{ 'images/guozhongwen.jpg' | relative_url}}" alt="photo" />
    </a>
    <p><strong>郭忠文</strong></p>
    <p>智能物联网团队负责人</p>
    <p>邮箱：guozhw@ouc.edu.cn</p>
  </div>
  <!-- <div class="arrow-down1"></div> -->
</div>

<div class="arrow-down-wrapper">
  <div class="arrow-down1"></div>
</div>

<div class="profile-row">

  <div class="profile-card">
    <a href="{{ '_pages/teacher/xiahui/' | relative_url}}">
      <img src="{{ 'images/xiahui.jpg' | relative_url}}" alt="photo" />
    </a>
    <p><strong>夏辉</strong></p>
    <p>研究方向：物联网、人工智能、隐私保护、边缘计算和智慧医疗</p>
    <p>邮箱：xiahui@ouc.edu.cn</p>
  </div>
  <!-- <div class="arrow-down2"></div> -->
</div>

<div class="profile-row">
  <div class="profile-card">
    <a href="{{ '/_pages/teacher/yujiaping/' | relative_url}}">
      <img src="{{ '/images/yujiaping.jpg' | relative_url}}" alt="photo" />
    </a>
    <p><strong>于佳平</strong></p>
    <p>研究方向：边缘计算场景下的资源跨域协同, Web3, DID</p>
    <p>邮箱：yujiaping@ouc.edu.cn</p>
  </div>
  <div class="profile-card">
    <a href="{{ '_pages/teacher/chenshuzhen/' | relative_url}}">
      <img src="{{ '/images/chenshuzhen.jpg' | relative_url}}" alt="photo" />
    </a>
    <p><strong>陈姝祯</strong></p>
    <p>研究方向：边缘智能与隐私计算</p>
    <p>邮箱：szchen@ouc.edu.cn</p>
  </div>
  <div class="profile-card">
    <a href="{{ '_pages/teacher/fuyu' | relative_url}}">
      <img src="{{ 'images/fuyu.png' | relative_url}}" alt="photo" />
    </a>
    <p><strong>傅宇</strong></p>
    <p>研究方向：医学影像处理与智能计算</p>
    <p>邮箱：fuyu@ouc.edu.cn</p>
  </div>
  

</div>

<style>
  /* .profile-row {
    display: flex;
    gap: 40px;
    flex-wrap: wrap;
    justify-content: center;
    align-items: flex-start;
  } */

  .profile-card {
    flex: 1;
    min-width: 220px;
    max-width: 300px;
    text-align: center;
    padding: 16px;
  }

  .profile-card img {
    width: 100%;
    max-width: 180px;
    height: auto;
    border-radius: 8px;
    margin-bottom: 12px;
    border: 1px solid #ddd;
    border-radius: 12px;
    transition: transform 0.2s ease;
  }

  .profile-card a:hover img {
    transform: scale(1.05);
  }

  .profile-card p {
    margin: 6px 0;
  }

  /* .arrow-down1 {
  width: 0;
  height: 0;
  border-left: 20px solid transparent;
  border-right: 20px solid transparent;
  border-top: 20px solid #888;
  position: absolute;
  top: 37%; 
  left: 50%;
  transform: translateX(-50%);
  margin-top: 5px;
}
.arrow-down2 {
  width: 0;
  height: 0;
  border-left: 20px solid transparent;
  border-right: 20px solid transparent;
  border-top: 20px solid #888;
  position: absolute;
  top: 66%; 
  left: 50%;
  transform: translateX(-50%);
  margin-top: 5px;
} */

/* mradd */
.profile-row {
  display: flex;
  gap: 40px;
  flex-wrap: wrap;
  justify-content: center;
  align-items: flex-start;
  position: relative;
}

/* 箭头外层：水平居中，和上下行留点空隙 */
.arrow-down-wrapper {
  display: flex;
  justify-content: center;
  margin: 20px 0;
}

/* 美化后的箭头 */
.arrow-down1 {
  width: 0;
  height: 0;
  border-left: 12px solid transparent;
  border-right: 12px solid transparent;
  border-top: 16px solid rgb(52, 96, 219);  /* 主色调 */
  filter: drop-shadow(0 2px 4px rgba(0, 0, 0, 0.2));
  animation: bounce 2s infinite;
}

/* 轻微上下浮动动画 */
@keyframes bounce {
  0%, 20%, 50%, 80%, 100% { transform: translateY(0); }
  40% { transform: translateY(8px); }
  60% { transform: translateY(4px); }
}

/* 保持响应式：手机屏幕时箭头和间距适当缩小 */
@media (max-width: 768px) {
  .arrow-down-wrapper {
    margin: 16px 0;
  }
  .arrow-down1 {
    border-left-width: 10px;
    border-right-width: 10px;
    border-top-width: 14px;
  }
}

</style>
