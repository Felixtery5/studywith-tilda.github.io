---
layout: page
title: "Lesson 11"
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

<div class="lesson-section" id="vocab">
  <div class="vocab-card" style="display:block">
    <p><strong>篮球 lánqiú</strong> <audio controls><source src="audio1.mp3" type="audio/mpeg"></audio></p>
    <div style="text-align:center;">
      <button onclick="switchCard('vocab', -1)">&lt; BACK</button>
      <img src="image1.png" alt="词汇图" width="100">
      <button onclick="switchCard('vocab', 1)">NEXT &gt;</button>
    </div>
    <p><strong>Ex:</strong> 他会打篮球。</p>
  </div>
  <div class="vocab-card" style="display:none">
    <p><strong>足球 zúqiú</strong> <audio controls><source src="audio1.mp3" type="audio/mpeg"></audio></p>
    <div style="text-align:center;">
      <button onclick="switchCard('vocab', -1)">&lt; BACK</button>
      <img src="image1.png" alt="词汇图" width="100">
      <button onclick="switchCard('vocab', 1)">NEXT &gt;</button>
    </div>
    <p><strong>Ex:</strong> 他会踢足球。</p>
  </div>
  <div class="vocab-card" style="display:none">
    <p><strong>乒乓球 pīngpāngqiú</strong> <audio controls><source src="audio1.mp3" type="audio/mpeg"></audio></p>
    <div style="text-align:center;">
      <button onclick="switchCard('vocab', -1)">&lt; BACK</button>
      <img src="image1.png" alt="词汇图" width="100">
      <button onclick="switchCard('vocab', 1)">NEXT &gt;</button>
    </div>
    <p><strong>Ex:</strong> 他会乒乓球。</p>
  </div>
  <div class="vocab-card" style="display:none">
    <p><strong>羽毛球 yǔmáoqiú</strong> <audio controls><source src="audio1.mp3" type="audio/mpeg"></audio></p>
    <div style="text-align:center;">
      <button onclick="switchCard('vocab', -1)">&lt; BACK</button>
      <img src="image1.png" alt="词汇图" width="100">
      <button onclick="switchCard('vocab', 1)">NEXT &gt;</button>
    </div>
    <p><strong>Ex:</strong> 他会打羽毛球。</p>
  </div>
</div>

<div class="lesson-section" id="practice1" style="display:none">
  <div class="vocab-card practice-card" style="display:block">
    <p>根据图片和音频填写正确的生词：</p>
    <div class="practice-question">
      <img src="practice1_img1.png" alt="练习图1" width="120">
      <audio controls><source src="practice1_audio1.mp3" type="audio/mpeg"></audio>
      <input type="text" placeholder="填写生词"><button onclick="checkAnswer(this, '篮球')">提交</button><span></span>
    </div>
    <div style="text-align:center;">
      <button onclick="switchCard('practice1', -1)">&lt; BACK</button>
      <button onclick="switchCard('practice1', 1)">NEXT &gt;</button>
    </div>
  </div>
  <div class="vocab-card practice-card" style="display:none">
    <p>根据图片和音频填写正确的生词：</p>
    <div class="practice-question">
      <img src="practice1_img2.png" alt="练习图2" width="120">
      <audio controls><source src="practice1_audio2.mp3" type="audio/mpeg"></audio>
      <input type="text" placeholder="填写生词"><button onclick="checkAnswer(this, '游泳')">提交</button><span></span>
    </div>
    <div style="text-align:center;">
      <button onclick="switchCard('practice1', -1)">&lt; BACK</button>
      <button onclick="switchCard('practice1', 1)">NEXT &gt;</button>
    </div>
  </div>
  <div class="vocab-card practice-card" style="display:none">
    <p>根据图片和音频填写正确的生词：</p>
    <div class="practice-question">
      <img src="practice1_img3.png" alt="练习图3" width="120">
      <audio controls><source src="practice1_audio3.mp3" type="audio/mpeg"></audio>
      <input type="text" placeholder="填写生词"><button onclick="checkAnswer(this, '踢足球')">提交</button><span></span>
    </div>
    <div style="text-align:center;">
      <button onclick="switchCard('practice1', -1)">&lt; BACK</button>
      <button onclick="switchCard('practice1', 1)">NEXT &gt;</button>
    </div>
  </div>
  <div class="vocab-card practice-card" style="display:none">
    <p>根据图片和音频填写正确的生词：</p>
    <div class="practice-question">
      <img src="practice1_img4.png" alt="练习图4" width="120">
      <audio controls><source src="practice1_audio4.mp3" type="audio/mpeg"></audio>
      <input type="text" placeholder="填写生词"><button onclick="checkAnswer(this, '唱歌')">提交</button><span></span>
    </div>
    <div style="text-align:center;">
      <button onclick="switchCard('practice1', -1)">&lt; BACK</button>
      <button onclick="switchCard('practice1', 1)">NEXT &gt;</button>
    </div>
  </div>
  <div class="vocab-card practice-card" style="display:none">
    <p>根据图片和音频填写正确的生词：</p>
    <div class="practice-question">
      <img src="practice1_img5.png" alt="练习图5" width="120">
      <audio controls><source src="practice1_audio5.mp3" type="audio/mpeg"></audio>
      <input type="text" placeholder="填写生词"><button onclick="checkAnswer(this, '跑步')">提交</button><span></span>
    </div>
    <div style="text-align:center;">
      <button onclick="switchCard('practice1', -1)">&lt; BACK</button>
      <button onclick="switchCard('practice1', 1)">NEXT &gt;</button>
    </div>
  </div>
</div>

<script>
function showSection(sectionId) {
  const sections = document.querySelectorAll('.lesson-section');
  sections.forEach(sec => sec.style.display = 'none');
  document.getElementById(sectionId).style.display = 'block';
  resetCards(sectionId);
}

function switchCard(sectionId, direction) {
  const cards = document.querySelectorAll(`#${sectionId} .vocab-card`);
  let current = Array.from(cards).findIndex(c => c.style.display !== 'none');
  cards[current].style.display = 'none';
  let next = current + direction;
  if (next < 0) next = cards.length - 1;
  if (next >= cards.length) next = 0;
  cards[next].style.display = 'block';
}

function resetCards(sectionId) {
  const cards = document.querySelectorAll(`#${sectionId} .vocab-card`);
  cards.forEach((c, i) => c.style.display = i === 0 ? 'block' : 'none');
}

function checkAnswer(button, correct) {
  const input = button.previousElementSibling.value.trim();
  const resultSpan = button.nextElementSibling;
  resultSpan.textContent = input === correct ? '✅' : '❎';
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
  font-size: 14px;
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
input {
  margin: 5px;
  padding: 5px;
}
</style>
