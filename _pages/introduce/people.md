<div class="profile-row">

  <div class="profile-card">
    <a href="teacher/xiahui">
      <img src="{{ 'images/xiahui.jpg' | relative_url }}" alt="photo" />
    </a>
    <p><strong>夏辉</strong></p>
    <p>研究方向：人工智能与大数据分析</p>
    <p>邮箱：xiahui@ouc.edu.cn</p>
  </div>

  <div class="profile-card">
    <!-- 空卡片，可填写其他内容 -->
  </div>

</div>

<div class="profile-row">

  <div class="profile-card">
    <a href="teacher/youyang">
      <img src="images/youyang.png" alt="photo" />
    </a>
    <p><strong>尤洋（副教授）</strong></p>
    <p>研究方向：人工智能、强化学习、智能博弈、网络信息安全</p>
    <p>邮箱：youyang@ouc.edu.cn</p>
  </div>

  <div class="profile-card">
    <a href="teacher/fuyu">
      <img src="images/fuyu.png" alt="photo" />
    </a>
    <p><strong>傅宇</strong></p>
    <p>研究方向：医学影像处理与智能计算</p>
    <p>邮箱：fuyu@ouc.edu.cn</p>
  </div>

</div>

<div class="profile-row">

  <div class="profile-card">
    <a href="teacher/chenshuzhen.html">
      <img src="images/chenshuzhen.jpg" alt="photo" />
    </a>
    <p><strong>陈姝祯</strong></p>
    <p>研究方向：边缘智能与隐私计算</p>
    <p>邮箱：szchen@ouc.edu.cn</p>
  </div>

  <div class="profile-card">
    <a href="teacher/yujiaping">
      <img src="images/yujiaping.jpg" alt="photo" />
    </a>
    <p><strong>于佳平</strong></p>
    <p>研究方向：边缘计算场景下的资源跨域协同, Web3, DID</p>
    <p>邮箱：yujiaping@ouc.edu.cn</p>
  </div>

</div>

<style>
  .profile-row {
    display: flex;
    gap: 40px;
    flex-wrap: wrap;
    justify-content: center;
    align-items: flex-start;
  }

  .profile-card {
    flex: 1;
    min-width: 220px;
    max-width: 300px;
    text-align: center;
    padding: 16px;
    border: 1px solid #ddd;
    border-radius: 12px;
    box-shadow: 2px 2px 8px rgba(0, 0, 0, 0.1);
  }

  .profile-card img {
    width: 100%;
    max-width: 180px;
    height: auto;
    border-radius: 8px;
    margin-bottom: 12px;
    transition: transform 0.2s ease;
  }

  .profile-card a:hover img {
    transform: scale(1.05);
  }

  .profile-card p {
    margin: 6px 0;
  }
</style>
