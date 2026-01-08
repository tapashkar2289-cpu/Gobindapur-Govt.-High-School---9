<!DOCTYPE html><html lang="bn">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Gobindapur Govt. High School</title>
  <style>
    body { margin: 0; font-family: Arial, sans-serif; background: #f4f6f8; }
    header { background: #0b5ed7; color: white; padding: 15px; text-align: center; }
    nav { background: #084298; padding: 10px; text-align: center; }
    nav a, nav button { color: white; margin: 0 10px; text-decoration: none; font-weight: bold; border: none; cursor: pointer; background: #084298; padding: 5px 10px; border-radius: 5px; }
    .container { padding: 15px; }
    .card { background: white; padding: 15px; margin-bottom: 15px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
    h2 { margin-top: 0; color: #0b5ed7; }
    ul { padding-left: 20px; }
    input, textarea { width: 100%; padding: 8px; margin-bottom: 10px; }
    footer { background: #0b5ed7; color: white; text-align: center; padding: 10px; }
    button { background: #0b5ed7; color: white; border: none; padding: 8px 12px; border-radius: 5px; cursor: pointer; }
  </style>
</head>
<body><header>
  <h1>Gobindapur Govt. High School</h1>
  <p>Official School Website</p>
</header><nav>
  <a href="#notice">নোটিশ</a>
  <a href="#news">খবর</a>
  <a href="#students">শিক্ষার্থী</a>
  <button onclick="adminLogin()">🔐 Admin Login</button>
</nav><div class="container">  <div class="card" id="notice">
    <h2>📢 নোটিশ বোর্ড</h2>
    <ul id="noticeList"></ul>
    <div id="adminNotice" style="display:none;">
      <h3>নতুন নোটিশ যোগ করুন (Admin)</h3>
      <input type="text" id="noticeInput" placeholder="নোটিশ লিখুন" />
      <button onclick="addNotice()">যোগ করুন</button>
    </div>
  </div>  <div class="card" id="news">
    <h2>📰 স্কুল খবর</h2>
    <ul id="newsList"></ul>
    <div id="adminNews" style="display:none;">
      <h3>নতুন খবর যোগ করুন (Admin)</h3>
      <input type="text" id="newsInput" placeholder="খবর লিখুন" />
      <button onclick="addNews()">যোগ করুন</button>
    </div>
  </div>  <div class="card" id="students">
    <h2>👨‍🎓 শিক্ষার্থী তালিকা</h2>
    <ul id="studentList">
      <li>শিক্ষার্থী ১</li>
      <li>শিক্ষার্থী ২</li>
    </ul>
  </div></div><footer>
  <p>© 2026 Gobindapur Govt. High School</p>
</footer><script>
const adminPassword = "1234";

function adminLogin() {
  const userPass = prompt("Admin Password দিন");
  if (userPass === adminPassword) {
    document.getElementById('adminNotice').style.display = 'block';
    document.getElementById('adminNews').style.display = 'block';
    alert("Admin mode চালু হয়েছে");
  } else if (userPass !== null) {
    alert("ভুল পাসওয়ার্ড");
  }
}

function addNotice() {
  const input = document.getElementById('noticeInput');
  const list = document.getElementById('noticeList');
  if (input.value !== '') {
    const li = document.createElement('li');
    li.textContent = input.value;
    list.appendChild(li);
    saveNotices();
    input.value = '';
  }
}

function saveNotices() {
  const notices = [];
  document.querySelectorAll('#noticeList li').forEach(li => notices.push(li.textContent));
  localStorage.setItem('notices', JSON.stringify(notices));
}

function loadNotices() {
  const data = localStorage.getItem('notices');
  if (data) {
    JSON.parse(data).forEach(text => {
      const li = document.createElement('li');
      li.textContent = text;
      document.getElementById('noticeList').appendChild(li);
    });
  }
}

function addNews() {
  const input = document.getElementById('newsInput');
  const list = document.getElementById('newsList');
  if (input.value !== '') {
    const li = document.createElement('li');
    li.textContent = input.value;
    list.appendChild(li);
    saveNews();
    input.value = '';
  }
}

function saveNews() {
  const news = [];
  document.querySelectorAll('#newsList li').forEach(li => news.push(li.textContent));
  localStorage.setItem('news', JSON.stringify(news));
}

function loadNews() {
  const data = localStorage.getItem('news');
  if (data) {
    JSON.parse(data).forEach(text => {
      const li = document.createElement('li');
      li.textContent = text;
      document.getElementById('newsList').appendChild(li);
    });
  }
}

// Load saved notices and news on page load
window.onload = function() {
  loadNotices();
  loadNews();
}
</script></body>
</html>
