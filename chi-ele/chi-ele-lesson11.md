---
layout: page
title: Lesson 11
subtitle: 你会打篮球吗？
permalink: /chi-ele/chi-ele-lesson11/
---

<div class="lesson-nav">
  <!-- 按钮容器 -->
  <div class="nav-items">
    <button onclick="showSection('vocab')">生词</button>
    <button onclick="showSection('practice1')">练习</button>
    <button onclick="showSection('grammar')">语言点</button>
    <button onclick="showSection('practice2')">练习</button>
    <button onclick="showSection('listening')">视听说</button>
    <button onclick="showSection('practice3')">练习</button>
    <button onclick="showSection('culture')">文化体验</button>
    <button onclick="showSection('homework')">作业</button>
  </div>
  <!-- 小屏下显示的下拉菜单 -->
  <select class="nav-select" onchange="selectSection(this.value)">
    <option value="">Choose</option>
    <option value="vocab">生词</option>
    <option value="practice1">生词练习</option>
    <option value="grammar">语言点</option>
    <option value="practice2">语言点练习</option>
    <option value="listening">视听说</option>
    <option value="practice3">视听说练习</option>
    <option value="culture">文化体验</option>
    <option value="homework">作业</option>
  </select>
</div>


<hr>

<!-- 生词区 -->
<div class="lesson-section" id="vocab">
  <div class="vocab-card" style="display:block">
    <!-- 词汇图片，居中 -->
    <div class="nav-btns" style="text-align: center;">
      <img 
        src="/chi-ele/lesson11/vocab/1YunDong.jpg" 
        alt="运动" 
        width="100"
      >
    </div>
    <div class="nav-btns" style="text-align: center;">
      <img 
        src="/chi-ele/lesson11/vocab/1YunDong-photo.jpg" 
        alt="运动" 
        width="150"
      >
    </div>
    <!-- 音频 -->
    <audio controls style="display: block; margin: 10px auto;">
      <source src="/chi-ele/lesson11/vocab/1YunDong.m4a" type="audio/mp4">
    </audio>
    <!-- 示例句 -->
    <!-- <p><strong>例:</strong> 我喜欢篮球。</p> -->
    <!-- 翻页按钮 -->
    <div class="nav-btns" style="text-align: center; margin-top: 15px;">
      <button onclick="switchCard('vocab', -1)">BACK</button>
      <button onclick="switchCard('vocab', 1)">NEXT</button>
    </div>
  </div>
  <div class="vocab-card" style="display:none">
    <!-- 词汇图片，居中 -->
    <div class="nav-btns" style="text-align: center;">
      <img 
        src="/chi-ele/lesson11/vocab/2LanQiu.jpg" 
        alt="篮球" 
        width="100"
      >
    </div>
    <div class="nav-btns" style="text-align: center;">
      <img 
        src="/chi-ele/lesson11/vocab/2LanQiu-photo.jpg" 
        alt="篮球" 
        width="150"
      >
    </div>
    <!-- 音频 -->
    <audio controls style="display: block; margin: 10px auto;">
      <source src="/chi-ele/lesson11/vocab/2LanQiu.m4a" type="audio/mp4">
    </audio>
    <!-- 示例句 -->
    <!-- <p><strong>例:</strong> 我喜欢篮球。</p> -->
    <!-- 翻页按钮 -->
    <div class="nav-btns" style="text-align: center; margin-top: 15px;">
      <button onclick="switchCard('vocab', -1)">BACK</button>
      <button onclick="switchCard('vocab', 1)">NEXT</button>
    </div>
  </div>
  <div class="vocab-card" style="display:none">
    <!-- 词汇图片，居中 -->
    <div class="nav-btns" style="text-align: center;">
      <img 
        src="/chi-ele/lesson11/vocab/3PaiQiu.jpg" 
        alt="排球" 
        width="100"
      >
    </div>
    <div class="nav-btns" style="text-align: center;">
      <img 
        src="/chi-ele/lesson11/vocab/3PaiQiu-photo.jpg" 
        alt="排球" 
        width="150"
      >
    </div>
    <!-- 音频 -->
    <audio controls style="display: block; margin: 10px auto;">
      <source src="/chi-ele/lesson11/vocab/3PaiQiu.m4a" type="audio/mp4">
    </audio>
    <!-- 示例句 -->
    <!-- <p><strong>例:</strong> 我喜欢篮球。</p> -->
    <!-- 翻页按钮 -->
    <div class="nav-btns" style="text-align: center; margin-top: 15px;">
      <button onclick="switchCard('vocab', -1)">BACK</button>
      <button onclick="switchCard('vocab', 1)">NEXT</button>
    </div>
  </div>
  <div class="vocab-card" style="display:none">
    <!-- 词汇图片，居中 -->
    <div class="nav-btns" style="text-align: center;">
      <img 
        src="/chi-ele/lesson11/vocab/4WangQiu.jpg" 
        alt="网球" 
        width="100"
      >
    </div>
    <div class="nav-btns" style="text-align: center;">
      <img 
        src="/chi-ele/lesson11/vocab/4WangQiu-photo.jpg" 
        alt="网球" 
        width="150"
      >
    </div>
    <!-- 音频 -->
    <audio controls style="display: block; margin: 10px auto;">
      <source src="/chi-ele/lesson11/vocab/4WangQiu.m4a" type="audio/mp4">
    </audio>
    <!-- 示例句 -->
    <!-- <p><strong>例:</strong> 我喜欢篮球。</p> -->
    <!-- 翻页按钮 -->
    <div class="nav-btns" style="text-align: center; margin-top: 15px;">
      <button onclick="switchCard('vocab', -1)">BACK</button>
      <button onclick="switchCard('vocab', 1)">NEXT</button>
    </div>
  </div>
  <div class="vocab-card" style="display:none">
    <!-- 词汇图片，居中 -->
    <div class="nav-btns" style="text-align: center;">
      <img 
        src="/chi-ele/lesson11/vocab/5PingPangQiujpg.jpg" 
        alt="乒乓球" 
        width="100"
      >
    </div>
    <div class="nav-btns" style="text-align: center;">
      <img 
        src="/chi-ele/lesson11/vocab/5PingPangQiu-photo.jpg" 
        alt="乒乓球" 
        width="150"
      >
    </div>
    <!-- 音频 -->
    <audio controls style="display: block; margin: 10px auto;">
      <source src="/chi-ele/lesson11/vocab/5PingPangQiu.m4a" type="audio/mp4">
    </audio>
    <!-- 示例句 -->
    <!-- <p><strong>例:</strong> 我喜欢篮球。</p> -->
    <!-- 翻页按钮 -->
    <div class="nav-btns" style="text-align: center; margin-top: 15px;">
      <button onclick="switchCard('vocab', -1)">BACK</button>
      <button onclick="switchCard('vocab', 1)">NEXT</button>
    </div>
  </div>
  <div class="vocab-card" style="display:none">
    <!-- 词汇图片，居中 -->
    <div class="nav-btns" style="text-align: center;">
      <img 
        src="/chi-ele/lesson11/vocab/6打.jpg" 
        alt="打" 
        width="100"
      >
    </div>
    <div class="nav-btns" style="text-align: center;">
      <img 
        src="/chi-ele/lesson11/vocab/6Da-photo.jpg" 
        alt="打" 
        width="150"
      >
    </div>
    <!-- 音频 -->
    <audio controls style="display: block; margin: 10px auto;">
      <source src="/chi-ele/lesson11/vocab/6Da.m4a" type="audio/mp4">
    </audio>
    <!-- 示例句 -->
    <p><strong>例:</strong> 我喜欢打篮球。</p>
    <p><strong>例:</strong> 我不会打乒乓球。</p>
    <!-- 翻页按钮 -->
    <div class="nav-btns" style="text-align: center; margin-top: 15px;">
      <button onclick="switchCard('vocab', -1)">BACK</button>
      <button onclick="switchCard('vocab', 1)">NEXT</button>
    </div>
  </div>
  <div class="vocab-card" style="display:none">
    <!-- 词汇图片，居中 -->
    <div class="nav-btns" style="text-align: center;">
      <img 
        src="/chi-ele/lesson11/vocab/7ZuQiu.jpg" 
        alt="足球" 
        width="100"
      >
    </div>
    <div class="nav-btns" style="text-align: center;">
      <img 
        src="/chi-ele/lesson11/vocab/7ZuQiu-photo.jpg" 
        alt="足球" 
        width="150"
      >
    </div>
    <!-- 音频 -->
    <audio controls style="display: block; margin: 10px auto;">
      <source src="/chi-ele/lesson11/vocab/7ZuQiu.m4a" type="audio/mp4">
    </audio>
    <!-- 示例句 -->
    <!-- <p><strong>例:</strong> 我喜欢篮球。</p> -->
    <!-- 翻页按钮 -->
    <div class="nav-btns" style="text-align: center; margin-top: 15px;">
      <button onclick="switchCard('vocab', -1)">BACK</button>
      <button onclick="switchCard('vocab', 1)">NEXT</button>
    </div>
  </div>
  <div class="vocab-card" style="display:none">
    <!-- 词汇图片，居中 -->
    <div class="nav-btns" style="text-align: center;">
      <img 
        src="/chi-ele/lesson11/vocab/8Gen.jpg" 
        alt="踢" 
        width="100"
      >
    </div>
    <div class="nav-btns" style="text-align: center;">
      <img 
        src="/chi-ele/lesson11/vocab/8Gen-Photo.jpg" 
        alt="踢" 
        width="150"
      >
    </div>
    <!-- 音频 -->
    <audio controls style="display: block; margin: 10px auto;">
      <source src="/chi-ele/lesson11/vocab/8Gen.m4a" type="audio/mp4">
    </audio>
    <!-- 示例句 -->
    <p><strong>例:</strong> 我喜欢踢足球。</p>
    <!-- 翻页按钮 -->
    <div class="nav-btns" style="text-align: center; margin-top: 15px;">
      <button onclick="switchCard('vocab', -1)">BACK</button>
      <button onclick="switchCard('vocab', 1)">NEXT</button>
    </div>
  </div>
  <div class="vocab-card" style="display:none">
    <!-- 词汇图片，居中 -->
    <div class="nav-btns" style="text-align: center;">
      <img 
        src="/chi-ele/lesson11/vocab/9YouYong.jpg" 
        alt="游泳" 
        width="100"
      >
    </div>
    <div class="nav-btns" style="text-align: center;">
      <img 
        src="/chi-ele/lesson11/vocab/9YouYong-Photo.jpg" 
        alt="游泳" 
        width="150"
      >
    </div>
    <!-- 音频 -->
    <audio controls style="display: block; margin: 10px auto;">
      <source src="/chi-ele/lesson11/vocab/9YouYong.m4a" type="audio/mp4">
    </audio>
    <!-- 示例句 -->
    <p><strong>例:</strong> 我不会游泳。</p>
    <!-- 翻页按钮 -->
    <div class="nav-btns" style="text-align: center; margin-top: 15px;">
      <button onclick="switchCard('vocab', -1)">BACK</button>
      <button onclick="switchCard('vocab', 1)">NEXT</button>
    </div>
  </div>
  <div class="vocab-card" style="display:none">
    <!-- 词汇图片，居中 -->
    <div class="nav-btns" style="text-align: center;">
      <img 
        src="/chi-ele/lesson11/vocab/10PaoBu.jpg" 
        alt="跑步" 
        width="100"
      >
    </div>
    <div class="nav-btns" style="text-align: center;">
      <img 
        src="/chi-ele/lesson11/vocab/10PaoBu-Photo.jpg" 
        alt="跑步" 
        width="150"
      >
    </div>
    <!-- 音频 -->
    <audio controls style="display: block; margin: 10px auto;">
      <source src="/chi-ele/lesson11/vocab/10PaoBu.m4a" type="audio/mp4">
    </audio>
    <!-- 示例句 -->
    <p><strong>例:</strong> 他喜欢跑步。</p>
    <!-- 翻页按钮 -->
    <div class="nav-btns" style="text-align: center; margin-top: 15px;">
      <button onclick="switchCard('vocab', -1)">BACK</button>
      <button onclick="switchCard('vocab', 1)">NEXT</button>
    </div>
  </div>
  <div class="vocab-card" style="display:none">
    <!-- 词汇图片，居中 -->
    <div class="nav-btns" style="text-align: center;">
      <img 
        src="/chi-ele/lesson11/vocab/11QiZiXingChe.jpg" 
        alt="骑自行车" 
        width="100"
      >
    </div>
    <div class="nav-btns" style="text-align: center;">
      <img 
        src="/chi-ele/lesson11/vocab/11QiZiXingChe-Photo.jpg" 
        alt="骑自行车" 
        width="150"
      >
    </div>
    <!-- 音频 -->
    <audio controls style="display: block; margin: 10px auto;">
      <source src="/chi-ele/lesson11/vocab/11QiZiXingChe.m4a" type="audio/mp4">
    </audio>
    <!-- 示例句 -->
    <p><strong>例:</strong> 她很喜欢骑自行车。。</p>
    <!-- 翻页按钮 -->
    <div class="nav-btns" style="text-align: center; margin-top: 15px;">
      <button onclick="switchCard('vocab', -1)">BACK</button>
      <button onclick="switchCard('vocab', 1)">NEXT</button>
    </div>
  </div>
</div>

<!-- 练习1 -->
<div class="lesson-section" id="practice1" style="display:none">
  <div class="vocab-card practice-card" style="display:block">
    <p>根据图片和音频填写正确的生词：</p>
    <div class="practice-question" style="text-align: center;">
      <img src="/chi-ele/lesson11/vocab/11QiZiXingChe-Photo.jpg" alt="骑自行车" width="150" >
      <audio controls style="display: block; margin: 10px auto;">
        <source src="/chi-ele/lesson11/vocab/11QiZiXingChe.m4a" type="audio/mp4">
      </audio>
    </div>
    <div class="practice-question" style="text-align: center;">
      <input
        type="text"
        placeholder="填写生词"
        data-answer="骑自行车"
        onkeydown="if(event.key==='Enter'){ checkAnswer(this.nextElementSibling, this.dataset.answer) }"
      >
      <button type="button" onclick="checkAnswer(this, this.previousElementSibling.dataset.answer)">SUBMIT</button>
      <span class="feedback"></span>
    </div>
    <div class="nav-btns">
      <button onclick="switchCard('practice1', -1)">BACK</button>
      <button onclick="switchCard('practice1', 1)">NEXT</button>
    </div>
  </div>
  <div class="vocab-card practice-card" style="display:none">
    <p>根据图片和音频填写正确的生词：</p>
    <div class="practice-question" style="text-align: center;">
      <img src="/chi-ele/lesson11/vocab/1YunDong-photo.jpg" alt="骑自行车" width="150" >
      <audio controls style="display: block; margin: 10px auto;">
        <source src="/chi-ele/lesson11/vocab/1YunDong.m4a" type="audio/mp4">
      </audio>
    </div>
    <div class="practice-question" style="text-align: center;">
      <input
        type="text"
        placeholder="填写生词"
        data-answer="运动"
        onkeydown="if(event.key==='Enter'){ checkAnswer(this.nextElementSibling, this.dataset.answer) }"
      >
      <button type="button" onclick="checkAnswer(this, this.previousElementSibling.dataset.answer)">SUBMIT</button>
      <span class="feedback"></span>
    </div>
    <div class="nav-btns">
      <button onclick="switchCard('practice1', -1)">BACK</button>
      <button onclick="switchCard('practice1', 1)">NEXT</button>
    </div>
  </div>
  <div class="vocab-card practice-card" style="display:none">
    <p>根据图片和音频填写正确的生词：</p>
    <div class="practice-question" style="text-align: center;">
      <img src="/chi-ele/lesson11/vocab/10PaoBu-Photo.jpg" alt="骑自行车" width="150" >
      <audio controls style="display: block; margin: 10px auto;">
        <source src="/chi-ele/lesson11/vocab/10PaoBu.m4a" type="audio/mp4">
      </audio>
    </div>
    <div class="practice-question" style="text-align: center;">
      <input
        type="text"
        placeholder="填写生词"
        data-answer="跑步"
        onkeydown="if(event.key==='Enter'){ checkAnswer(this.nextElementSibling, this.dataset.answer) }"
      >
      <button type="button" onclick="checkAnswer(this, this.previousElementSibling.dataset.answer)">SUBMIT</button>
      <span class="feedback"></span>
    </div>
    <div class="nav-btns">
      <button onclick="switchCard('practice1', -1)">BACK</button>
      <button onclick="switchCard('practice1', 1)">NEXT</button>
    </div>
  </div>
  <div class="vocab-card practice-card" style="display:none">
    <p>根据图片和音频填写正确的生词：</p>
    <div class="practice-question" style="text-align: center;">
      <img src="/chi-ele/lesson11/vocab/6Da-photo.jpg" alt="骑自行车" width="150" >
      <audio controls style="display: block; margin: 10px auto;">
        <source src="/chi-ele/lesson11/vocab/6Da.m4a" type="audio/mp4">
      </audio>
    </div>
    <div class="practice-question" style="text-align: center;">
      <input
        type="text"
        placeholder="填写生词"
        data-answer="打"
        onkeydown="if(event.key==='Enter'){ checkAnswer(this.nextElementSibling, this.dataset.answer) }"
      >
      <button type="button" onclick="checkAnswer(this, this.previousElementSibling.dataset.answer)">SUBMIT</button>
      <span class="feedback"></span>
    </div>
    <div class="nav-btns">
      <button onclick="switchCard('practice1', -1)">BACK</button>
      <button onclick="switchCard('practice1', 1)">NEXT</button>
    </div>
  </div>
  <div class="vocab-card practice-card" style="display:none">
    <p>根据图片和音频填写正确的生词：</p>
    <div class="practice-question" style="text-align: center;">
      <img src="/chi-ele/lesson11/vocab/2LanQiu-photo.jpg" alt="骑自行车" width="150" >
      <audio controls style="display: block; margin: 10px auto;">
        <source src="/chi-ele/lesson11/vocab/2LanQiu.m4a" type="audio/mp4">
      </audio>
    </div>
    <div class="practice-question" style="text-align: center;">
      <input
        type="text"
        placeholder="填写生词"
        data-answer="篮球"
        onkeydown="if(event.key==='Enter'){ checkAnswer(this.nextElementSibling, this.dataset.answer) }"
      >
      <button type="button" onclick="checkAnswer(this, this.previousElementSibling.dataset.answer)">SUBMIT</button>
      <span class="feedback"></span>
    </div>
    <div class="nav-btns">
      <button onclick="switchCard('practice1', -1)">BACK</button>
      <button onclick="switchCard('practice1', 1)">NEXT</button>
    </div>
  </div>
  <div class="vocab-card practice-card" style="display:none">
    <p>根据图片和音频填写正确的生词：</p>
    <div class="practice-question" style="text-align: center;">
      <img src="/chi-ele/lesson11/vocab/9YouYong-Photo.jpg" alt="骑自行车" width="150" >
      <audio controls style="display: block; margin: 10px auto;">
        <source src="/chi-ele/lesson11/vocab/9YouYong.m4a" type="audio/mp4">
      </audio>
    </div>
    <div class="practice-question" style="text-align: center;">
      <input
        type="text"
        placeholder="填写生词"
        data-answer="游泳"
        onkeydown="if(event.key==='Enter'){ checkAnswer(this.nextElementSibling, this.dataset.answer) }"
      >
      <button type="button" onclick="checkAnswer(this, this.previousElementSibling.dataset.answer)">SUBMIT</button>
      <span class="feedback"></span>
    </div>
    <div class="nav-btns">
      <button onclick="switchCard('practice1', -1)">BACK</button>
      <button onclick="switchCard('practice1', 1)">NEXT</button>
    </div>
  </div>
  <div class="vocab-card practice-card" style="display:none">
    <p>根据图片和音频填写正确的生词：</p>
    <div class="practice-question" style="text-align: center;">
      <img src="/chi-ele/lesson11/vocab/5PingPangQiu-photo.jpg" alt="骑自行车" width="150" >
      <audio controls style="display: block; margin: 10px auto;">
        <source src="/chi-ele/lesson11/vocab/5PingPangQiu.m4a" type="audio/mp4">
      </audio>
    </div>
    <div class="practice-question" style="text-align: center;">
      <input
        type="text"
        placeholder="填写生词"
        data-answer="乒乓球"
        onkeydown="if(event.key==='Enter'){ checkAnswer(this.nextElementSibling, this.dataset.answer) }"
      >
      <button type="button" onclick="checkAnswer(this, this.previousElementSibling.dataset.answer)">SUBMIT</button>
      <span class="feedback"></span>
    </div>
    <div class="nav-btns">
      <button onclick="switchCard('practice1', -1)">BACK</button>
      <button onclick="switchCard('practice1', 1)">NEXT</button>
    </div>
  </div>
  <div class="vocab-card practice-card" style="display:none">
    <p>根据图片和音频填写正确的生词：</p>
    <div class="practice-question" style="text-align: center;">
      <img src="/chi-ele/lesson11/vocab/8Gen-Photo.jpg" alt="骑自行车" width="150" >
      <audio controls style="display: block; margin: 10px auto;">
        <source src="/chi-ele/lesson11/vocab/8Gen.m4a" type="audio/mp4">
      </audio>
    </div>
    <div class="practice-question" style="text-align: center;">
      <input
        type="text"
        placeholder="填写生词"
        data-answer="踢"
        onkeydown="if(event.key==='Enter'){ checkAnswer(this.nextElementSibling, this.dataset.answer) }"
      >
      <button type="button" onclick="checkAnswer(this, this.previousElementSibling.dataset.answer)">SUBMIT</button>
      <span class="feedback"></span>
    </div>
    <div class="nav-btns">
      <button onclick="switchCard('practice1', -1)">BACK</button>
      <button onclick="switchCard('practice1', 1)">NEXT</button>
    </div>
  </div>
  <div class="vocab-card practice-card" style="display:none">
    <p>根据图片和音频填写正确的生词：</p>
    <div class="practice-question" style="text-align: center;">
      <img src="/chi-ele/lesson11/vocab/4WangQiu-photo.jpg" alt="骑自行车" width="150" >
      <audio controls style="display: block; margin: 10px auto;">
        <source src="/chi-ele/lesson11/vocab/4WangQiu.m4a" type="audio/mp4">
      </audio>
    </div>
    <div class="practice-question" style="text-align: center;">
      <input
        type="text"
        placeholder="填写生词"
        data-answer="网球"
        onkeydown="if(event.key==='Enter'){ checkAnswer(this.nextElementSibling, this.dataset.answer) }"
      >
      <button type="button" onclick="checkAnswer(this, this.previousElementSibling.dataset.answer)">SUBMIT</button>
      <span class="feedback"></span>
    </div>
    <div class="nav-btns">
      <button onclick="switchCard('practice1', -1)">BACK</button>
      <button onclick="switchCard('practice1', 1)">NEXT</button>
    </div>
  </div>
  <div class="vocab-card practice-card" style="display:none">
    <p>根据图片和音频填写正确的生词：</p>
    <div class="practice-question" style="text-align: center;">
      <img src="/chi-ele/lesson11/vocab/3PaiQiu-photo.jpg" alt="骑自行车" width="150" >
      <audio controls style="display: block; margin: 10px auto;">
        <source src="/chi-ele/lesson11/vocab/3PaiQiu.m4a" type="audio/mp4">
      </audio>
    </div>
    <div class="practice-question" style="text-align: center;">
      <input
        type="text"
        placeholder="填写生词"
        data-answer="排球"
        onkeydown="if(event.key==='Enter'){ checkAnswer(this.nextElementSibling, this.dataset.answer) }"
      >
      <button type="button" onclick="checkAnswer(this, this.previousElementSibling.dataset.answer)">SUBMIT</button>
      <span class="feedback"></span>
    </div>
    <div class="nav-btns">
      <button onclick="switchCard('practice1', -1)">BACK</button>
      <button onclick="switchCard('practice1', 1)">NEXT</button>
    </div>
  </div>
  <div class="vocab-card practice-card" style="display:none">
    <p>根据图片和音频填写正确的生词：</p>
    <div class="practice-question" style="text-align: center;">
      <img src="/chi-ele/lesson11/vocab/7ZuQiu-photo.jpg" alt="骑自行车" width="150" >
      <audio controls style="display: block; margin: 10px auto;">
        <source src="/chi-ele/lesson11/vocab/7ZuQiu.m4a" type="audio/mp4">
      </audio>
    </div>
    <div class="practice-question" style="text-align: center;">
      <input
        type="text"
        placeholder="填写生词"
        data-answer="足球"
        onkeydown="if(event.key==='Enter'){ checkAnswer(this.nextElementSibling, this.dataset.answer) }"
      >
      <button type="button" onclick="checkAnswer(this, this.previousElementSibling.dataset.answer)">SUBMIT</button>
      <span class="feedback"></span>
    </div>
    <div class="nav-btns">
      <button onclick="switchCard('practice1', -1)">BACK</button>
      <button onclick="switchCard('practice1', 1)">NEXT</button>
    </div>
  </div>
  <!-- 生词练习2 -->
  <div class="vocab-card practice-card" style="display:none">
    <p>请选择正确的图片或单词：</p>
    <div class="practice-question" style="text-align: center;">
      <img src="/chi-ele/lesson11/vocab/prac1/P1-Q1-A5.jpg" alt="picture" width="75" >
      <img src="/chi-ele/lesson11/vocab/prac1/P1-Q1-A1.jpg" alt="picture" width="100" >
      <img src="/chi-ele/lesson11/vocab/prac1/P1-Q1-A2.jpg" alt="picture" width="100" >
      <img src="/chi-ele/lesson11/vocab/prac1/P1-Q1-A3.jpg" alt="picture" width="100" >
      <img src="/chi-ele/lesson11/vocab/prac1/P1-Q1-A4.jpg" alt="picture" width="100" >
      <img src="/chi-ele/lesson11/vocab/prac1/P1-Q2-A8.jpg" alt="picture" width="25" >
    </div>
    <div class="practice-question" style="text-align: center;">
      <img src="/chi-ele/lesson11/vocab/prac1/P1-Q2-A9.jpg" alt="picture" width="50" >
      <img src="/chi-ele/lesson11/vocab/prac1/P1-Q2-A6.jpg" alt="picture" width="75" >
      <img src="/chi-ele/lesson11/vocab/prac1/P1-Q2-A7.jpg" alt="picture" width="50" >
      <img src="/chi-ele/lesson11/vocab/prac1/P1-Q3-A10.jpg" alt="picture" width="50" >
      <img src="/chi-ele/lesson11/vocab/prac1/P1-Q3-A11.jpg" alt="picture" width="100" >
    </div>
    <div class="practice-question" style="text-align: center;">
      <img src="/chi-ele/lesson11/vocab/prac1/1P1-Q1.jpg" alt="picture" width="500" >
    </div>
    <div class="practice-question" style="text-align: center;">
      <img src="/chi-ele/lesson11/vocab/prac1/1P1-Q2.jpg" alt="picture" width="500" >
    </div>
    <div class="practice-question" style="text-align: center;">
      <img src="/chi-ele/lesson11/vocab/prac1/1P1-Q3.jpg" alt="picture" width="500" >
    </div>
    <!-- 问题选择区域 -->
    <div class="matching-quiz">
      <div class="questions-container">
        <!-- 空格1 -->
        <div class="question" data-qid="1">
          <span class="question-number">1.</span>
          <select class="answer-select">
            <option value="">-- Option --</option>
            <option value="A">A</option>
            <option value="B">B</option>
            <option value="C">C</option>
            <option value="D">D</option>
            <option value="E">E</option>
            <option value="F">F</option>
            <option value="G">G</option>
            <option value="H">H</option>
            <option value="I">I</option>
            <option value="J">J</option>
            <option value="K">K</option>
          </select>
          <span class="feedback-icon"></span>
        </div>
        <!-- 空格2 -->
        <div class="question" data-qid="2">
          <span class="question-number">2.</span>
          <select class="answer-select">
            <option value="">-- Option --</option>
            <option value="A">A</option>
            <option value="B">B</option>
            <option value="C">C</option>
            <option value="D">D</option>
            <option value="E">E</option>
            <option value="F">F</option>
            <option value="G">G</option>
            <option value="H">H</option>
            <option value="I">I</option>
            <option value="J">J</option>
            <option value="K">K</option>
          </select>
          <span class="feedback-icon"></span>
        </div>
        <!-- 空格3 -->
        <div class="question" data-qid="3">
          <span class="question-number">3.</span>
          <select class="answer-select">
            <option value="">-- Option --</option>
            <option value="A">A</option>
            <option value="B">B</option>
            <option value="C">C</option>
            <option value="D">D</option>
            <option value="E">E</option>
            <option value="F">F</option>
            <option value="G">G</option>
            <option value="H">H</option>
            <option value="I">I</option>
            <option value="J">J</option>
            <option value="K">K</option>
          </select>
          <span class="feedback-icon"></span>
        </div>
        <!-- 空格4 -->
        <div class="question" data-qid="4">
          <span class="question-number">4.</span>
          <select class="answer-select">
            <option value="">-- Option --</option>
            <option value="A">A</option>
            <option value="B">B</option>
            <option value="C">C</option>
            <option value="D">D</option>
            <option value="E">E</option>
            <option value="F">F</option>
            <option value="G">G</option>
            <option value="H">H</option>
            <option value="I">I</option>
            <option value="J">J</option>
            <option value="K">K</option>
          </select>
          <span class="feedback-icon"></span>
        </div>
        <!-- 空格5 -->
        <div class="question" data-qid="5">
          <span class="question-number">5.</span>
          <select class="answer-select">
            <option value="">-- Option --</option>
            <option value="A">A</option>
            <option value="B">B</option>
            <option value="C">C</option>
            <option value="D">D</option>
            <option value="E">E</option>
            <option value="F">F</option>
            <option value="G">G</option>
            <option value="H">H</option>
            <option value="I">I</option>
            <option value="J">J</option>
            <option value="K">K</option>
          </select>
          <span class="feedback-icon"></span>
        </div>
        <!-- 空格6 -->
        <div class="question" data-qid="6">
          <span class="question-number">6.</span>
          <select class="answer-select">
            <option value="">-- Option --</option>
            <option value="A">A</option>
            <option value="B">B</option>
            <option value="C">C</option>
            <option value="D">D</option>
            <option value="E">E</option>
            <option value="F">F</option>
            <option value="G">G</option>
            <option value="H">H</option>
            <option value="I">I</option>
            <option value="J">J</option>
            <option value="K">K</option>
          </select>
          <span class="feedback-icon"></span>
        </div>
        <!-- 空格7 -->
        <div class="question" data-qid="7">
          <span class="question-number">7.</span>
          <select class="answer-select">
            <option value="">-- Option --</option>
            <option value="A">A</option>
            <option value="B">B</option>
            <option value="C">C</option>
            <option value="D">D</option>
            <option value="E">E</option>
            <option value="F">F</option>
            <option value="G">G</option>
            <option value="H">H</option>
            <option value="I">I</option>
            <option value="J">J</option>
            <option value="K">K</option>
          </select>
          <span class="feedback-icon"></span>
        </div>
        <!-- 空格8 -->
        <div class="question" data-qid="8">
          <span class="question-number">8.</span>
          <select class="answer-select">
            <option value="">-- Option --</option>
            <option value="A">A</option>
            <option value="B">B</option>
            <option value="C">C</option>
            <option value="D">D</option>
            <option value="E">E</option>
            <option value="F">F</option>
            <option value="G">G</option>
            <option value="H">H</option>
            <option value="I">I</option>
            <option value="J">J</option>
            <option value="K">K</option>
          </select>
          <span class="feedback-icon"></span>
        </div>
        <!-- 空格9 -->
        <div class="question" data-qid="9">
          <span class="question-number">9.</span>
          <select class="answer-select">
            <option value="">-- Option --</option>
            <option value="A">A</option>
            <option value="B">B</option>
            <option value="C">C</option>
            <option value="D">D</option>
            <option value="E">E</option>
            <option value="F">F</option>
            <option value="G">G</option>
            <option value="H">H</option>
            <option value="I">I</option>
            <option value="J">J</option>
            <option value="K">K</option>
          </select>
          <span class="feedback-icon"></span>
        </div>
        <!-- 空格10 -->
        <div class="question" data-qid="10">
          <span class="question-number">10.</span>
          <select class="answer-select">
            <option value="">-- Option --</option>
            <option value="A">A</option>
            <option value="B">B</option>
            <option value="C">C</option>
            <option value="D">D</option>
            <option value="E">E</option>
            <option value="F">F</option>
            <option value="G">G</option>
            <option value="H">H</option>
            <option value="I">I</option>
            <option value="J">J</option>
            <option value="K">K</option>
          </select>
          <span class="feedback-icon"></span>
        </div>
        <!-- 空格11 -->
        <div class="question" data-qid="11">
          <span class="question-number">11.</span>
          <select class="answer-select">
            <option value="">-- Option --</option>
            <option value="A">A</option>
            <option value="B">B</option>
            <option value="C">C</option>
            <option value="D">D</option>
            <option value="E">E</option>
            <option value="F">F</option>
            <option value="G">G</option>
            <option value="H">H</option>
            <option value="I">I</option>
            <option value="J">J</option>
            <option value="K">K</option>
          </select>
          <span class="feedback-icon"></span>
        </div>
      </div>
      <div class="practice-question" style="text-align: center;">
        <button type="button" onclick="checkMatchingAnswers()">SUBMIT</button>
        <button type="button" id="viewAnswerBtn" style="display:none" onclick="viewAnswers()">View Answer</button>
        <span class="feedback"></span>
      </div>
    </div>
    <div class="nav-btns">
      <button onclick="switchCard('practice1', -1)">BACK</button>
      <button onclick="switchCard('practice1', 1)">NEXT</button>
    </div>
    <div class="answer-key" style="display:none; margin-top:20px; padding:15px; background:#f5f5f5; border-radius:5px;">
      <h3>正确答案:</h3>
      <div id="correct-answers-list"></div>
    </div>
  </div>
</div>

<!-- 语言点 -->
<div class="lesson-section" id="grammar" style="display:none">
  <div class="vocab-card" style="display:block">
    <p><strong>又……又……</strong></p>
    <p><strong>Ex:</strong> 夏天又热又闷。</p>
    <div class="nav-btns">
      <button onclick="switchCard('grammar', -1)">BACK</button>
      <button onclick="switchCard('grammar', 1)">NEXT</button>
    </div>
  </div>
  <div class="vocab-card" style="display:none">
    <p><strong>又……又……</strong></p>
    <p><strong>Ex:</strong> 他学习又认真又努力。</p>
    <div class="nav-btns">
      <button onclick="switchCard('grammar', -1)">BACK</button>
      <button onclick="switchCard('grammar', 1)">NEXT</button>
    </div>
  </div>
</div>

<!-- 练习2 -->
<div class="lesson-section" id="practice2" style="display:none">
  <div class="vocab-card" style="display:block">
    <!-- 填写练习2内容 -->
    <div class="nav-btns">
      <button onclick="switchCard('practice2', -1)">BACK</button>
      <button onclick="switchCard('practice2', 1)">NEXT</button>
    </div>
  </div>
  <div class="vocab-card" style="display:none">
    <!-- 练习2 第2张卡 -->
    <div class="nav-btns">
      <button onclick="switchCard('practice2', -1)">BACK</button>
      <button onclick="switchCard('practice2', 1)">NEXT</button>
    </div>
  </div>
</div>

<!-- 视听说 -->
<div class="lesson-section" id="listening" style="display:none">
  <div class="vocab-card" style="display:block">
    <!-- 填写视听说内容 -->
    <div class="nav-btns">
      <button onclick="switchCard('listening', -1)">BACK</button>
      <button onclick="switchCard('listening', 1)">NEXT</button>
    </div>
  </div>
  <div class="vocab-card" style="display:none">
    <!-- 视听说 第2张卡 -->
    <div class="nav-btns">
      <button onclick="switchCard('listening', -1)">BACK</button>
      <button onclick="switchCard('listening', 1)">NEXT</button>
    </div>
  </div>
</div>

<!-- 练习3 -->
<div class="lesson-section" id="practice3" style="display:none">
  <div class="vocab-card" style="display:block">
    <!-- 填写练习3内容 -->
    <div class="nav-btns">
      <button onclick="switchCard('practice3', -1)">BACK</button>
      <button onclick="switchCard('practice3', 1)">NEXT</button>
    </div>
  </div>
  <div class="vocab-card" style="display:none">
    <!-- 练习3 第2张卡 -->
    <div class="nav-btns">
      <button onclick="switchCard('practice3', -1)">BACK</button>
      <button onclick="switchCard('practice3', 1)">NEXT</button>
    </div>
  </div>
</div>

<!-- 文化体验 -->
<div class="lesson-section" id="culture" style="display:none">
  <div class="vocab-card" style="display:block">
    <!-- 填写文化体验内容 -->
    <div class="nav-btns">
      <button onclick="switchCard('culture', -1)">BACK</button>
      <button onclick="switchCard('culture', 1)">NEXT</button>
    </div>
  </div>
  <div class="vocab-card" style="display:none">
    <!-- 文化体验 第2张卡 -->
    <div class="nav-btns">
      <button onclick="switchCard('culture', -1)">BACK</button>
      <button onclick="switchCard('culture', 1)">NEXT</button>
    </div>
  </div>
</div>

<!-- 作业 -->
<div class="lesson-section" id="homework" style="display:none">
  <div class="vocab-card" style="display:block">
    <!-- 填写作业内容 -->
    <div class="nav-btns">
      <button onclick="switchCard('homework', -1)">BACK</button>
      <button onclick="switchCard('homework', 1)">NEXT</button>
    </div>
  </div>
  <div class="vocab-card" style="display:none">
    <!-- 作业 第2张卡 -->
    <div class="nav-btns">
      <button onclick="switchCard('homework', -1)">BACK</button>
      <button onclick="switchCard('homework', 1)">NEXT</button>
    </div>
  </div>
</div>




<script>
  // 存储正确答案
const correctAnswers_vocab2 = {
  '1': 'B',
  '2': 'C',
  '3': 'D',
  '4': 'E',
  '5': 'A',
  '6': 'H',
  '7': 'I',
  '8': 'F',
  '9': 'G',
  '10': 'J',
  '11': 'K'
};
  // 已选择的选项
const selectedOptions = new Set();

function checkSelection(selectElement) {
  const selectedValue = selectElement.value;
  const questionId = selectElement.closest('.question').dataset.qid;
  
  // 清除之前的选择（如果有）
  if (selectElement.dataset.prevValue) {
    selectedOptions.delete(selectElement.dataset.prevValue);
  }
  
  // 检查是否已被选择
  if (selectedValue && selectedOptions.has(selectedValue)) {
    alert('This option has already been selected. Please choose another one.');
    selectElement.value = '';
    return;
  }
  
  // 更新选择
  if (selectedValue) {
    selectedOptions.add(selectedValue);
    selectElement.dataset.prevValue = selectedValue;
  }
  
  // 清除之前的反馈图标
  const feedbackIcon = selectElement.nextElementSibling;
  feedbackIcon.textContent = '';
  feedbackIcon.className = 'feedback-icon';
}

function checkMatchingAnswers() {
  const selects = document.querySelectorAll('.answer-select');
  let score = 0;
  
  selects.forEach(select => {
    const questionId = select.closest('.question').dataset.qid;
    const feedbackIcon = select.nextElementSibling;
    
    if (select.value === correctAnswers_vocab2[questionId]) {
      score++;
      feedbackIcon.textContent = '✅';
      feedbackIcon.className = 'feedback-icon correct';
    } else if (select.value) {
      feedbackIcon.textContent = '❌';
      feedbackIcon.className = 'feedback-icon incorrect';
    }
  });
  
  document.querySelector('.feedback').textContent = `你答对了 ${score} 题，共11题`;
  
  // 显示View Answer按钮
  document.getElementById('viewAnswerBtn').style.display = 'inline-block';
}

function viewAnswers() {
  const answerKey = document.querySelector('.answer-key');
  const answersList = document.getElementById('correct-answers-list');
  
  // 构建正确答案列表
  answersList.innerHTML = '';
  for (let i = 1; i <= 11; i++) {
    const div = document.createElement('div');
    div.textContent = `${i}. ${correctAnswers_vocab2[i]}`;
    answersList.appendChild(div);
  }
  
  // 显示答案区域
  answerKey.style.display = 'block';
}
  
  function showSection(id) {
    document.querySelectorAll('.lesson-section').forEach(sec => sec.style.display = 'none');
    document.getElementById(id).style.display = 'block';
    // 切换到新模块时重置卡片
    document.querySelectorAll('#'+id+' .vocab-card').forEach((c, i) => {
      c.style.display = i===0 ? 'block' : 'none';
    });
  }

  function switchCard(sectionId, dir) {
    const cards = Array.from(document.querySelectorAll('#'+sectionId+' .vocab-card'));
    const current = cards.findIndex(c => c.style.display==='block');
    cards[current].style.display = 'none';
    let next = current + dir;
    if (next < 0) next = cards.length - 1;
    if (next >= cards.length) next = 0;
    cards[next].style.display = 'block';
  }

  function checkAnswer(button, correct) {
    const inputEl    = button.previousElementSibling;
    const resultSpan = button.nextElementSibling;
    const userInput  = inputEl.value.trim();
    if (userInput === correct) {
      resultSpan.textContent = '✅ 正确！';
      resultSpan.style.color = 'green';
    } else {
      resultSpan.textContent = '❌ 错误，再试一次。';
      resultSpan.style.color = 'red';
    }
  }

  // 为所有选择框添加事件监听
document.querySelectorAll('.answer-select').forEach(select => {
  select.addEventListener('change', function() {
    checkSelection(this);
  });
});
  
</script>

<style>
.lesson-nav {
  background-color: #eef5fa;
  padding: 10px;
  border-radius: 8px;
  text-align: center;                /* 容器文本居中 */
}

.lesson-nav .nav-items {
  display: inline-flex;              /* 居中对齐用 inline-flex */
  gap: 8px;                          /* 按钮间距 */
  overflow-x: auto;
}

.lesson-nav button {
  padding: 6px 12px;
  border: none;
  background: #cce4ff;
  border-radius: 6px;
  cursor: pointer;
  white-space: nowrap;
}

.lesson-nav button:hover {
  background: #a3d0ff;
}

/* 下拉菜单默认隐藏 */
.lesson-nav .nav-select {
  display: none;
  padding: 6px 12px;
  border-radius: 6px;
  border: 1px solid #cce4ff;
  background: #cce4ff;
  cursor: pointer;
}

/* 小屏幕下的切换 */
@media (max-width: 768px) {
  .lesson-nav .nav-items {
    display: none;                   /* 隐藏按钮 */
  }
  .lesson-nav .nav-select {
    display: inline-block;           /* 显示下拉 */
  }
}

.vocab-card {
  border: 2px solid #073642;
  padding: 20px;
  border-radius: 20px;
  margin-top: 20px;
}
.practice-question {
  margin-top: 10px;
  align-items: flex-start;
}
.nav-btns {
  text-align: center;
  margin-top: 10px;
}
.nav-btns button {
  margin: 0 5px;
  padding: 6px 10px;
}
input {
  margin: 5px;
  padding: 5px;
}
.feedback {
  margin-left: 8px;
  font-weight: bold;
}

  /* 新增的选择题样式 */
.question {
  margin: 10px 0;
  display: flex;
  align-items: center;
}
.question-number {
  width: 30px;
  display: inline-block;
}
.answer-select {
  padding: 5px;
  margin: 0 10px;
}
.feedback-icon {
  margin-left: 10px;
  font-size: 20px;
}
.correct {
  color: green;
}
.incorrect {
  color: red;
}
</style>

<script>
  // 原有的 showSection, switchCard, checkAnswer …

  function selectSection(value) {
    if (!value) return;
    showSection(value);
    document.querySelector('.nav-select').value = "";
  }
</script>
