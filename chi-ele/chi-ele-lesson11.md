---
layout: page
title: Lesson 11
subtitle: 你会打篮球吗？
permalink: /chi-ele/chi-ele-lesson11/
---

<div class="lesson-nav">
  <button onclick="showSection('vocab')">生词</button>
  <button onclick="showSection('practice1')">练习</button>
  <button onclick="showSection('grammar')">语言点</button>
  <button onclick="showSection('practice2')">练习</button>
  <button onclick="showSection('listening')">视听说</button>
  <button onclick="showSection('practice3')">练习</button>
  <button onclick="showSection('culture')">文化体验</button>
  <button onclick="showSection('homework')">作业</button>
</div>

<hr>

<!-- 生词区 -->
<div class="lesson-section" id="vocab">
  <div class="vocab-card" style="display:block">
    <p><strong>篮球 lánqiú</strong> <audio controls><source src="audio1.mp3" type="audio/mpeg"></audio></p>
    <p><strong>Ex:</strong> 他会打篮球。</p>
    <div class="nav-btns">
      <button onclick="switchCard('vocab', -1)">BACK</button>
      <img src="image1.png" alt="篮球" width="100">
      <button onclick="switchCard('vocab', 1)">NEXT</button>
    </div>
  </div>
  <div class="vocab-card" style="display:none">
    <p><strong>足球 zúqiú</strong> <audio controls><source src="audio2.mp3" type="audio/mpeg"></audio></p>
    <p><strong>Ex:</strong> 他会踢足球。</p>
    <div class="nav-btns">
      <button onclick="switchCard('vocab', -1)">BACK</button>
      <img src="image2.png" alt="足球" width="100">
      <button onclick="switchCard('vocab', 1)">NEXT</button>
    </div>
  </div>
  <div class="vocab-card" style="display:none">
    <p><strong>乒乓球 pīngpāngqiú</strong> <audio controls><source src="audio3.mp3" type="audio/mpeg"></audio></p>
    <p><strong>Ex:</strong> 他会打乒乓球。</p>
    <div class="nav-btns">
      <button onclick="switchCard('vocab', -1)">BACK</button>
      <img src="image3.png" alt="乒乓球" width="100">
      <button onclick="switchCard('vocab', 1)">NEXT</button>
    </div>
  </div>
  <div class="vocab-card" style="display:none">
    <p><strong>羽毛球 yǔmáoqiú</strong> <audio controls><source src="audio4.mp3" type="audio/mpeg"></audio></p>
    <p><strong>Ex:</strong> 他会打羽毛球。</p>
    <div class="nav-btns">
      <button onclick="switchCard('vocab', -1)">BACK</button>
      <img src="image4.png" alt="羽毛球" width="100">
      <button onclick="switchCard('vocab', 1)">NEXT</button>
    </div>
  </div>
</div>

<!-- 练习1 -->
<div class="lesson-section" id="practice1" style="display:none">
  <div class="vocab-card practice-card" style="display:block">
    <p>根据图片和音频填写正确的生词：</p>
    <div class="practice-question">
      <img src="practice1_img1.png" alt="练习图1" width="120">
      <audio controls><source src="practice1_audio1.mp3" type="audio/mpeg"></audio>
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
    <div class="practice-question">
      <img src="practice1_img2.png" alt="练习图2" width="120">
      <audio controls><source src="practice1_audio2.mp3" type="audio/mpeg"></audio>
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

  <!-- 如果还有卡片，依此类推，确保 style 初始为 display:block/none，input 同样添加 data-answer/onkeydown -->
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
      resultSpan.textContent = '✔️';
      resultSpan.style.color = 'green';
    } else {
      resultSpan.textContent = '❌';
      resultSpan.style.color = 'red';
    }
  }
</script>

<style>
.lesson-nav {
  background-color: #eef5fa;
  padding: 10px;
  border-radius: 8px;
  text-align: center;
  font-weight: bold;
}
.lesson-nav button {
  margin: 0 8px;
  padding: 6px 12px;
  border: none;
  background: #cce4ff;
  border-radius: 6px;
  cursor: pointer;
}
.lesson-nav button:hover {
  background: #a3d0ff;
}
.vocab-card {
  border: 2px solid #073642;
  padding: 20px;
  border-radius: 20px;
  margin-top: 20px;
}
.practice-question {
  margin-top: 15px;
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
</style>
