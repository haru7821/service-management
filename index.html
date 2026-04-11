<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
<meta name="mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="theme-color" content="#105742">
<title>Vantive — Technical Service</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@300;400;500;600&family=DM+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
  :root {
    --purple:#72256b; --forest:#105742; --teal:#356962;
    --mint:#f0f7f3; --white:#ffffff; --border:#dce9e4;
    --text:#105742; --text-dim:#356962; --text-muted:#7aab9a;
    --danger:#c0392b; --success:#1e8f5e; --warn:#b07a1a;
  }
  *, *::before, *::after { margin:0; padding:0; box-sizing:border-box; }
  html, body { height:100%; height:100dvh; overflow:hidden; }
  body { font-family:'DM Sans',sans-serif; background:var(--white); color:var(--text); display:flex; flex-direction:column; overflow-x:hidden; }

  /* ── Nav ── */
  .top-nav { background:var(--white); border-bottom:1px solid var(--border); padding:0 20px; display:flex; align-items:center; height:52px; flex-shrink:0; box-shadow:0 1px 6px rgba(16,87,66,0.06); }
  .nav-logo { text-decoration:none; display:flex; align-items:center; }
  .nav-logo-img { height:22px; width:auto; object-fit:contain; }
  .nav-right { margin-left:auto; display:flex; align-items:center; gap:10px; }
  .user-info { font-size:12px; color:var(--text-dim); font-weight:500; }
  .user-role { font-size:10px; background:rgba(114,37,107,0.08); color:var(--purple); padding:2px 7px; border-radius:10px; font-weight:600; }

  /* ── Scroll body ── */
  .scroll-body { flex:1; overflow-y:auto; overflow-x:hidden; -webkit-overflow-scrolling:touch; }

  /* ── Login screen ── */
  .login-wrap { display:flex; align-items:center; justify-content:center; min-height:100%; padding:24px 20px; }
  .login-card {
    background:var(--white); border:1.5px solid var(--border); border-radius:16px;
    padding:36px 28px; width:100%; max-width:380px;
    box-shadow:0 8px 32px rgba(16,87,66,0.1);
  }
  .login-logo { text-align:center; margin-bottom:8px; }
  .login-logo img { height:28px; }
  .login-subtitle { text-align:center; font-size:13px; color:var(--text-muted); margin-bottom:28px; }
  .login-title { text-align:center; font-size:18px; font-weight:700; color:var(--forest); margin-bottom:4px; }

  /* ── Main screen ── */
  .main-wrap { display:none; }
  .hero { background:var(--mint); border-bottom:1px solid var(--border); padding:20px; flex-shrink:0; }
  .hero-title { font-size:20px; font-weight:700; color:var(--purple); }
  .hero-sub { font-size:13px; color:var(--text-dim); margin-top:4px; }
  .stats-row { display:flex; border-bottom:1px solid var(--border); flex-shrink:0; }
  .stat-block { flex:1; padding:14px 16px; border-right:1px solid var(--border); display:flex; align-items:center; gap:10px; }
  .stat-block:last-child { border-right:none; }
  .stat-icon { width:32px; height:32px; border-radius:8px; background:rgba(114,37,107,0.08); display:flex; align-items:center; justify-content:center; font-size:14px; flex-shrink:0; }
  .stat-label { font-size:10px; font-weight:600; text-transform:uppercase; letter-spacing:.06em; color:var(--text-muted); margin-bottom:2px; }
  .stat-value { font-family:'DM Mono',monospace; font-size:20px; color:var(--purple); line-height:1; }
  .wrapper { padding:14px; }
  .section-label { font-size:10px; font-weight:600; text-transform:uppercase; letter-spacing:.12em; color:var(--text-muted); margin-bottom:12px; display:flex; align-items:center; gap:8px; }
  .section-label::after { content:''; flex:1; height:1px; background:var(--border); }
  .hospital-grid { display:grid; grid-template-columns:1fr; gap:10px; margin-bottom:16px; }
  .hospital-card { background:var(--white); border:1.5px solid var(--border); border-radius:10px; padding:16px; cursor:pointer; transition:all .2s; position:relative; overflow:hidden; text-decoration:none; display:block; }
  .hospital-card::after { content:''; position:absolute; top:0; left:0; right:0; height:3px; background:linear-gradient(90deg,var(--purple),#a0358e); transform:scaleX(0); transform-origin:left; transition:transform .2s; border-radius:10px 10px 0 0; }
  .hospital-card:hover { border-color:var(--purple); box-shadow:0 4px 16px rgba(114,37,107,0.1); }
  .hospital-card:hover::after { transform:scaleX(1); }
  .hospital-card-id { font-family:'DM Mono',monospace; font-size:9px; color:var(--text-muted); margin-bottom:5px; text-transform:uppercase; }
  .hospital-card-name { font-size:16px; font-weight:600; color:var(--forest); margin-bottom:12px; }
  .hospital-card-meta { display:flex; gap:16px; }
  .meta-item { display:flex; flex-direction:column; gap:2px; }
  .meta-label { font-size:10px; font-weight:600; text-transform:uppercase; letter-spacing:.06em; color:var(--text-muted); }
  .meta-value { font-family:'DM Mono',monospace; font-size:20px; color:var(--purple); }
  .hospital-card-arrow { position:absolute; top:16px; right:16px; color:var(--border); font-size:16px; transition:all .2s; }
  .hospital-card:hover .hospital-card-arrow { color:var(--purple); }
  .add-card { background:var(--white); border:1.5px dashed var(--border); border-radius:10px; padding:16px; cursor:pointer; transition:all .2s; display:flex; align-items:center; gap:10px; min-height:72px; color:var(--text-muted); }
  .add-card:hover { border-color:var(--purple); color:var(--purple); background:rgba(114,37,107,0.03); }

  /* ── Forms ── */
  .form-group { margin-bottom:14px; }
  label { display:block; font-size:11px; font-weight:700; color:var(--text-dim); text-transform:uppercase; letter-spacing:.06em; margin-bottom:5px; }
  input[type="text"],input[type="email"],input[type="password"],select {
    width:100%; background:var(--mint); border:1.5px solid var(--border); border-radius:8px;
    padding:11px 12px; color:var(--forest); font-family:'DM Sans',sans-serif;
    font-size:16px; outline:none; transition:all .15s;
  }
  input::placeholder { color:var(--text-muted); }
  input:focus,select:focus { border-color:var(--purple); background:var(--white); }
  select option { background:var(--white); }

  /* ── Buttons ── */
  .btn { display:inline-flex; align-items:center; justify-content:center; gap:6px; border-radius:8px; font-family:'DM Sans',sans-serif; font-size:14px; font-weight:600; cursor:pointer; border:none; transition:all .15s; white-space:nowrap; }
  .btn-full { width:100%; height:48px; }
  .btn-primary { background:var(--purple); color:var(--white); }
  .btn-primary:hover { background:#5a1c54; }
  .btn-ghost { background:transparent; border:1.5px solid var(--border); color:var(--text-dim); padding:7px 14px; height:36px; }
  .btn-ghost:hover { border-color:var(--purple); color:var(--purple); }
  .btn-danger-ghost { background:transparent; border:1.5px solid var(--danger); color:var(--danger); padding:7px 14px; height:36px; }
  .btn-sm { height:32px; padding:0 12px; font-size:12px; }
  .btn-row { display:flex; gap:8px; justify-content:flex-end; margin-top:16px; }

  /* ── Modal ── */
  .modal-overlay { display:none; position:fixed; inset:0; background:rgba(16,87,66,0.3); backdrop-filter:blur(4px); z-index:100; align-items:flex-end; justify-content:center; touch-action:none; overflow:hidden; }
  .modal-overlay.open { display:flex; }
  .modal { background:var(--white); border-radius:16px 16px 0 0; width:100%; max-width:100%; max-height:90dvh; overflow-y:auto; overflow-x:hidden; touch-action:pan-y; padding:20px 16px; padding-bottom:max(20px,env(safe-area-inset-bottom)); position:relative; animation:slideUp .25s cubic-bezier(.32,.72,0,1); }
  .modal::before { content:''; position:absolute; top:0; left:0; right:0; height:4px; background:linear-gradient(90deg,var(--purple),#a0358e); border-radius:16px 16px 0 0; }
  .modal::after { content:''; position:absolute; top:7px; left:50%; transform:translateX(-50%); width:32px; height:4px; background:var(--border); border-radius:2px; }
  @keyframes slideUp { from{transform:translateY(100%);}to{transform:translateY(0);} }
  .modal-title { font-size:17px; font-weight:700; color:var(--forest); margin-bottom:14px; margin-top:6px; }
  .modal-title span { color:var(--purple); }
  .modal-close { position:absolute; top:10px; right:12px; background:none; border:none; color:var(--text-muted); font-size:18px; cursor:pointer; padding:5px 8px; border-radius:6px; }

  /* ── Info / Error ── */
  .info-box { background:var(--mint); border:1px solid var(--border); border-left:3px solid var(--purple); border-radius:0 8px 8px 0; padding:10px 13px; font-size:12px; color:var(--text-dim); line-height:1.6; margin-bottom:12px; }
  .error-msg { color:var(--danger); font-size:12px; margin-top:6px; text-align:center; min-height:18px; }

  /* ── Admin: 사용자 목록 ── */
  .user-list { display:flex; flex-direction:column; gap:8px; max-height:260px; overflow-y:auto; touch-action:pan-y; }
  .user-item { background:var(--mint); border:1px solid var(--border); border-radius:8px; padding:11px 13px; display:flex; align-items:center; gap:10px; }
  .user-item-info { flex:1; min-width:0; }
  .user-item-name { font-size:13px; font-weight:600; color:var(--forest); }
  .user-item-email { font-size:11px; color:var(--text-muted); overflow:hidden; text-overflow:ellipsis; white-space:nowrap; }
  .user-item-role { font-size:10px; padding:2px 7px; border-radius:10px; font-weight:600; flex-shrink:0; }
  .role-admin { background:rgba(114,37,107,0.1); color:var(--purple); }
  .role-engineer { background:rgba(53,105,98,0.1); color:var(--teal); }

  /* ── Spinner ── */
  .spinner { width:18px; height:18px; border:2px solid var(--border); border-top-color:var(--purple); border-radius:50%; animation:spin .7s linear infinite; display:inline-block; }
  @keyframes spin { to{transform:rotate(360deg);} }
  .loading-wrap { display:flex; align-items:center; justify-content:center; padding:40px; gap:10px; color:var(--text-muted); font-size:13px; }

  /* ── Toast ── */
  .toast { position:fixed; left:12px; right:12px; bottom:max(14px,calc(8px + env(safe-area-inset-bottom))); background:var(--white); border:1.5px solid var(--border); border-radius:10px; padding:12px 16px; font-size:13px; font-weight:500; color:var(--forest); z-index:999; transform:translateY(60px); opacity:0; transition:all .3s; box-shadow:0 4px 16px rgba(16,87,66,0.1); }
  .toast.show { transform:translateY(0); opacity:1; }
  .toast.success { border-color:var(--success); }
  .toast.error   { border-color:var(--danger); }

  /* ── Admin 탭 ── */
  .admin-tabs { display:flex; border-bottom:1px solid var(--border); margin-bottom:14px; }
  .admin-tab { padding:8px 14px; font-size:12px; font-weight:600; color:var(--text-muted); cursor:pointer; border-bottom:2px solid transparent; margin-bottom:-1px; }
  .admin-tab.active { color:var(--purple); border-bottom-color:var(--purple); }
  .admin-panel { display:none; }
  .admin-panel.active { display:block; }

  @media(min-width:600px){
    .login-wrap { background:var(--mint); }
    .hero { padding:24px 32px; }
    .wrapper { padding:20px 32px 60px; }
    .hospital-grid { grid-template-columns:repeat(auto-fill,minmax(280px,1fr)); }
    .stats-row { }
    input[type="text"],input[type="email"],input[type="password"],select { font-size:14px; }
    .modal-overlay { align-items:center; }
    .modal { border-radius:14px; padding:28px; max-width:460px; animation:slideUpD .2s ease; }
    .modal::after { display:none; }
    @keyframes slideUpD { from{transform:translateY(12px);opacity:0;}to{transform:translateY(0);opacity:1;} }
  }
</style>
</head>
<body>

<!-- ── Nav ── -->
<nav class="top-nav" id="mainNav" style="display:none">
  <a class="nav-logo" href="#"><img src="" alt="Vantive" class="nav-logo-img" id="navLogoImg"></a>
  <div class="nav-right">
    <span class="user-info" id="userNameDisplay"></span>
    <span class="user-role" id="userRoleDisplay"></span>
    <button class="btn btn-ghost btn-sm" onclick="openModal('adminModal')" id="adminBtn" style="display:none">⚙ 관리</button>
    <button class="btn btn-ghost btn-sm" onclick="signOut()">로그아웃</button>
  </div>
</nav>

<!-- ── 로그인 화면 ── -->
<div class="scroll-body" id="loginScreen">
  <div class="login-wrap">
    <div class="login-card">
      <div class="login-logo"><img src="" alt="Vantive" id="loginLogoImg" style="height:28px;margin:0 auto"></div>
      <div class="login-title" style="margin-top:16px">Technical Service</div>
      <div class="login-subtitle">엔지니어 로그인</div>
      <div class="form-group"><label>이메일</label><input type="email" id="loginEmail" placeholder="email@example.com" autocomplete="email"></div>
      <div class="form-group"><label>비밀번호</label><input type="password" id="loginPassword" placeholder="비밀번호 입력" autocomplete="current-password"></div>
      <div class="error-msg" id="loginError"></div>
      <button class="btn btn-primary btn-full" style="margin-top:8px" onclick="doLogin()">로그인</button>
    </div>
  </div>
</div>

<!-- ── 메인 화면 ── -->
<div class="scroll-body main-wrap" id="mainScreen">
  <div class="hero">
    <div class="hero-title">Technical Service</div>
    <div class="hero-sub">병원별 장비 서비스 내역 관리 시스템</div>
  </div>
  <div class="stats-row">
    <div class="stat-block"><div class="stat-icon">🏥</div><div><div class="stat-label">Hospitals</div><div class="stat-value" id="statHospitals">—</div></div></div>
    <div class="stat-block"><div class="stat-icon">🔧</div><div><div class="stat-label">Equipment</div><div class="stat-value" id="statEquipment">—</div></div></div>
    <div class="stat-block"><div class="stat-icon">📋</div><div><div class="stat-label">Records</div><div class="stat-value" id="statRecords">—</div></div></div>
  </div>
  <div class="wrapper">
    <div class="section-label">병원 선택</div>
    <div class="hospital-grid" id="hospitalGrid">
      <div class="loading-wrap"><div class="spinner"></div> 불러오는 중...</div>
    </div>
    <div class="info-box" id="accessInfo" style="display:none"></div>
  </div>
</div>

<!-- ── 관리자 모달 ── -->
<div class="modal-overlay" id="adminModal">
  <div class="modal" style="max-width:480px">
    <div class="modal-title">관리자 <span>설정</span></div>
    <button class="modal-close" onclick="closeModal('adminModal')">✕</button>

    <div class="admin-tabs">
      <div class="admin-tab active" onclick="switchAdminTab('users')">엔지니어 관리</div>
      <div class="admin-tab" onclick="switchAdminTab('add')">계정 추가</div>
      <div class="admin-tab" onclick="switchAdminTab('hospital')">병원 추가</div>
    </div>

    <!-- 엔지니어 목록 -->
    <div class="admin-panel active" id="panel-users">
      <div class="user-list" id="userList"><div class="loading-wrap"><div class="spinner"></div></div></div>
    </div>

    <!-- 계정 추가 -->
    <div class="admin-panel" id="panel-add">
      <div class="form-group"><label>이름</label><input type="text" id="newUserName" placeholder="홍길동"></div>
      <div class="form-group"><label>이메일</label><input type="email" id="newUserEmail" placeholder="engineer@example.com"></div>
      <div class="form-group"><label>비밀번호</label><input type="password" id="newUserPw" placeholder="6자 이상"></div>
      <div class="form-group"><label>권한</label>
        <select id="newUserRole">
          <option value="engineer">엔지니어</option>
          <option value="admin">관리자</option>
        </select>
      </div>
      <div class="form-group"><label>담당 Account (쉼표로 구분)</label><input type="text" id="newUserAccounts" placeholder="부산대학교병원, 세브란스병원"></div>
      <div class="error-msg" id="addUserError"></div>
      <div class="btn-row"><button class="btn btn-primary" onclick="addUser()">계정 생성</button></div>
    </div>

    <!-- 병원 추가 -->
    <div class="admin-panel" id="panel-hospital">
      <div class="form-group"><label>병원명</label><input type="text" id="newHospitalName" placeholder="예: 부산대학교병원"></div>
      <div class="form-group"><label>병원 ID (영문, 하이픈 허용)</label><input type="text" id="newHospitalId" placeholder="예: pusan-univ-hospital"></div>
      <div class="btn-row"><button class="btn btn-primary" onclick="addHospital()">추가</button></div>
    </div>
  </div>
</div>

<!-- 엔지니어 Account 편집 모달 -->
<div class="modal-overlay" id="editUserModal">
  <div class="modal">
    <div class="modal-title">담당 <span>Account 편집</span></div>
    <button class="modal-close" onclick="closeModal('editUserModal')">✕</button>
    <div id="editUserInfo" style="font-size:13px;color:var(--text-dim);margin-bottom:12px"></div>
    <div class="form-group"><label>담당 Account (쉼표로 구분, 비우면 전체)</label><input type="text" id="editUserAccounts" placeholder="부산대학교병원, 세브란스병원"></div>
    <div class="form-group"><label>권한</label>
      <select id="editUserRole"><option value="engineer">엔지니어</option><option value="admin">관리자</option></select>
    </div>
    <input type="hidden" id="editUserUid">
    <div class="btn-row">
      <button class="btn btn-ghost" onclick="closeModal('editUserModal')">취소</button>
      <button class="btn btn-primary" onclick="saveUserEdit()">저장</button>
    </div>
  </div>
</div>

<div class="toast" id="toast"></div>

<script type="module">
import { initializeApp }     from 'https://www.gstatic.com/firebasejs/10.12.0/firebase-app.js';
import { getDatabase, ref, set, get, onValue, push, remove }
  from 'https://www.gstatic.com/firebasejs/10.12.0/firebase-database.js';
import { getAuth, signInWithEmailAndPassword, createUserWithEmailAndPassword,
         signOut as fbSignOut, onAuthStateChanged }
  from 'https://www.gstatic.com/firebasejs/10.12.0/firebase-auth.js';

const FIREBASE_CONFIG = {
  apiKey:           'AIzaSyAj11Y8Z5lFRufGVjoZqo7vfIGCnsduH-o',
  authDomain:       'service-management-7aff4.firebaseapp.com',
  databaseURL:      'https://service-management-7aff4-default-rtdb.asia-southeast1.firebasedatabase.app',
  projectId:        'service-management-7aff4',
  storageBucket:    'service-management-7aff4.firebasestorage.app',
  messagingSenderId:'121578077990',
  appId:            '1:121578077990:web:2b79e88c751f9c9aadcbe7'
};

// 로고 base64 (hospital.html과 동일)
const LOGO_SRC = document.querySelector('#loginLogoImg')?.src || '';

const app  = initializeApp(FIREBASE_CONFIG, 'vantive-index');
const db   = getDatabase(app);
const auth = getAuth(app);

let currentUser = null;   // Firebase user
let currentProfile = null; // DB 프로필 {name, role, accounts:[]}

// ── 로고 설정 ──
function setLogos(src){
  document.querySelectorAll('.nav-logo-img, #loginLogoImg, #navLogoImg').forEach(el=>{
    if(src) el.src = src;
  });
}
// hospital.html과 같은 origin에서 logo를 가져올 방법이 없으므로
// index.html 자체에서 base64 인라인 (hospital.html과 동일 base64)
fetch('hospital.html').then(r=>r.text()).then(html=>{
  const m = html.match(/nav-logo-img" src="([^"]+)"/);
  if(m) setLogos(m[1]);
}).catch(()=>{});

// ── Auth 상태 감시 ──
onAuthStateChanged(auth, async user => {
  if(user){
    currentUser = user;
    const snap = await get(ref(db, `users/${user.uid}`));
    if(snap.exists()){
      currentProfile = snap.val();
    } else {
      // 프로필 없으면 기본 engineer로 생성
      currentProfile = { name: user.email, role:'engineer', accounts:[] };
      await set(ref(db,`users/${user.uid}`), currentProfile);
    }
    showMain();
  } else {
    currentUser = null; currentProfile = null;
    showLogin();
  }
});

function showLogin(){
  document.getElementById('loginScreen').style.display = 'block';
  document.getElementById('mainScreen').style.display  = 'none';
  document.getElementById('mainNav').style.display     = 'none';
}
function showMain(){
  document.getElementById('loginScreen').style.display = 'none';
  document.getElementById('mainScreen').style.display  = 'block';
  document.getElementById('mainNav').style.display     = 'flex';
  document.getElementById('userNameDisplay').textContent = currentProfile?.name || currentUser.email;
  document.getElementById('userRoleDisplay').textContent = currentProfile?.role === 'admin' ? '관리자' : '엔지니어';
  if(currentProfile?.role === 'admin'){
    document.getElementById('adminBtn').style.display = 'inline-flex';
  }
  loadHospitals();
}

// ── 로그인 ──
window.doLogin = async function(){
  const email = document.getElementById('loginEmail').value.trim();
  const pw    = document.getElementById('loginPassword').value;
  const errEl = document.getElementById('loginError');
  errEl.textContent = '';
  if(!email||!pw){ errEl.textContent='이메일과 비밀번호를 입력하세요.'; return; }
  try {
    await signInWithEmailAndPassword(auth, email, pw);
  } catch(e){
    errEl.textContent = e.code === 'auth/invalid-credential' ? '이메일 또는 비밀번호가 올바르지 않습니다.' : e.message;
  }
};
document.getElementById('loginPassword').addEventListener('keydown', e=>{ if(e.key==='Enter') window.doLogin(); });

window.signOut = async function(){
  await fbSignOut(auth);
};

// ── 병원 목록 로드 ──
async function loadHospitals(){
  const grid = document.getElementById('hospitalGrid');
  grid.innerHTML = '<div class="loading-wrap"><div class="spinner"></div> 불러오는 중...</div>';

  const snap = await get(ref(db,'hospitals'));
  const data = snap.exists() ? snap.val() : {};
  const hospitals = Object.entries(data).map(([id,h])=>({id,...h}));

  document.getElementById('statHospitals').textContent = hospitals.length;

  // 엔지니어는 담당 Account가 있는 병원만 접근
  // (Account가 어느 병원에 속하는지는 equipment 데이터에서 판단)
  // Admin은 모두 표시
  const isAdmin = currentProfile?.role === 'admin';
  const myAccounts = currentProfile?.accounts || []; // [] = 전체(어드민 only)

  if(!isAdmin && myAccounts.length === 0){
    grid.innerHTML = '';
    document.getElementById('accessInfo').style.display = 'block';
    document.getElementById('accessInfo').textContent = '담당 Account가 지정되지 않았습니다. 관리자에게 문의하세요.';
    document.getElementById('statHospitals').textContent = '0';
    document.getElementById('statEquipment').textContent = '0';
    document.getElementById('statRecords').textContent = '0';
    return;
  }

  let totalEq = 0, totalRec = 0;
  grid.innerHTML = '';

  for(const h of hospitals){
    const eqSnap  = await get(ref(db,`equipment/${h.id}`));
    const recSnap = await get(ref(db,`records/${h.id}`));
    const allEq   = eqSnap.exists()  ? Object.values(eqSnap.val())  : [];
    const allRec  = recSnap.exists() ? Object.values(recSnap.val()) : [];

    // 담당 Account 필터
    const myEq  = isAdmin ? allEq  : allEq.filter(e=>myAccounts.includes(e.accountName||''));
    const mySns = new Set(myEq.map(e=>e.serialNumber));
    const myRec = isAdmin ? allRec : allRec.filter(r=>mySns.has(r.serialNumber));

    if(!isAdmin && myEq.length === 0) continue; // 담당 장비 없으면 병원 숨김

    totalEq  += myEq.length;
    totalRec += myRec.length;

    const a = document.createElement('a');
    a.className = 'hospital-card';
    a.href = `hospital.html?id=${h.id}`;
    a.innerHTML = `
      <div class="hospital-card-id"># ${h.id}</div>
      <div class="hospital-card-name">${h.name}</div>
      <div class="hospital-card-meta">
        <div class="meta-item"><span class="meta-label">장비</span><span class="meta-value">${myEq.length}</span></div>
        <div class="meta-item"><span class="meta-label">서비스</span><span class="meta-value">${myRec.length}</span></div>
      </div>
      <div class="hospital-card-arrow">↗</div>`;
    grid.appendChild(a);
  }

  if(grid.children.length === 0){
    grid.innerHTML = '<div class="loading-wrap" style="color:var(--text-muted)">담당 병원이 없습니다.</div>';
  } else if(isAdmin){
    // 병원 추가 버튼
    const addBtn = document.createElement('div');
    addBtn.className = 'add-card';
    addBtn.innerHTML = '<span style="font-size:22px">+</span><span style="font-size:13px;font-weight:600">병원 추가</span>';
    addBtn.onclick = ()=>{ switchAdminTab('hospital'); openModal('adminModal'); };
    grid.appendChild(addBtn);
  }

  document.getElementById('statEquipment').textContent = totalEq;
  document.getElementById('statRecords').textContent   = totalRec;
}

// ── 관리자: 엔지니어 목록 ──
async function loadUserList(){
  const list = document.getElementById('userList');
  list.innerHTML = '<div class="loading-wrap"><div class="spinner"></div></div>';
  const snap = await get(ref(db,'users'));
  if(!snap.exists()){ list.innerHTML='<div style="padding:16px;text-align:center;color:var(--text-muted);font-size:13px">등록된 사용자가 없습니다.</div>'; return; }
  const users = Object.entries(snap.val()).map(([uid,u])=>({uid,...u}));
  list.innerHTML = users.map(u=>`
    <div class="user-item">
      <div class="user-item-info">
        <div class="user-item-name">${u.name||u.email||'—'}</div>
        <div class="user-item-email">${u.email||''}</div>
        <div style="font-size:11px;color:var(--text-muted);margin-top:3px">
          ${u.accounts&&u.accounts.length>0 ? u.accounts.join(', ') : '전체 접근'}
        </div>
      </div>
      <span class="user-item-role ${u.role==='admin'?'role-admin':'role-engineer'}">${u.role==='admin'?'관리자':'엔지니어'}</span>
      <button class="btn btn-ghost btn-sm" onclick="openEditUser('${u.uid}','${(u.name||'').replace(/'/g,"\\'")}','${(u.accounts||[]).join(',')}','${u.role||'engineer'}')">편집</button>
    </div>`).join('');
}

window.openEditUser = function(uid, name, accounts, role){
  document.getElementById('editUserUid').value = uid;
  document.getElementById('editUserInfo').textContent = `엔지니어: ${name}`;
  document.getElementById('editUserAccounts').value = accounts;
  document.getElementById('editUserRole').value = role;
  openModal('editUserModal');
};

window.saveUserEdit = async function(){
  const uid      = document.getElementById('editUserUid').value;
  const accounts = document.getElementById('editUserAccounts').value.split(',').map(a=>a.trim()).filter(Boolean);
  const role     = document.getElementById('editUserRole').value;
  await set(ref(db,`users/${uid}/accounts`), accounts);
  await set(ref(db,`users/${uid}/role`), role);
  closeModal('editUserModal');
  showToast('저장 완료','success');
  loadUserList();
};

window.addUser = async function(){
  const name     = document.getElementById('newUserName').value.trim();
  const email    = document.getElementById('newUserEmail').value.trim();
  const pw       = document.getElementById('newUserPw').value;
  const role     = document.getElementById('newUserRole').value;
  const accounts = document.getElementById('newUserAccounts').value.split(',').map(a=>a.trim()).filter(Boolean);
  const errEl    = document.getElementById('addUserError');
  errEl.textContent = '';
  if(!name||!email||!pw){ errEl.textContent='이름, 이메일, 비밀번호를 모두 입력하세요.'; return; }
  if(pw.length < 6){ errEl.textContent='비밀번호는 6자 이상이어야 합니다.'; return; }
  try {
    // 별도 앱으로 계정 생성 (현재 로그인 유지)
    const app2 = initializeApp(FIREBASE_CONFIG, 'vantive-temp-'+Date.now());
    const auth2 = getAuth(app2);
    const cred = await createUserWithEmailAndPassword(auth2, email, pw);
    await set(ref(db,`users/${cred.user.uid}`), {name, email, role, accounts});
    await fbSignOut(auth2);
    ['newUserName','newUserEmail','newUserPw','newUserAccounts'].forEach(id=>document.getElementById(id).value='');
    showToast(`${name} 계정 생성 완료`,'success');
    switchAdminTab('users');
    loadUserList();
  } catch(e){ errEl.textContent = e.message; }
};

window.addHospital = async function(){
  const name = document.getElementById('newHospitalName').value.trim();
  const id   = document.getElementById('newHospitalId').value.trim();
  if(!name||!id){ showToast('병원명과 ID를 입력하세요.','error'); return; }
  if(!/^[a-z0-9\-]+$/.test(id)){ showToast('ID는 영문 소문자, 숫자, 하이픈만 가능합니다.','error'); return; }
  await set(ref(db,`hospitals/${id}`), {name, createdAt:new Date().toISOString()});
  document.getElementById('newHospitalName').value='';
  document.getElementById('newHospitalId').value='';
  showToast(`${name} 추가 완료`,'success');
  loadHospitals();
  closeModal('adminModal');
};

// ── 관리자 탭 ──
window.switchAdminTab = function(name){
  document.querySelectorAll('.admin-tab').forEach((t,i)=>t.classList.toggle('active',['users','add','hospital'][i]===name));
  document.querySelectorAll('.admin-panel').forEach(p=>p.classList.toggle('active',p.id===`panel-${name}`));
  if(name==='users') loadUserList();
};

// ── Modal ──
window.openModal  = id=>{ document.getElementById(id).classList.add('open'); if(id==='adminModal') loadUserList(); };
window.closeModal = id=>document.getElementById(id).classList.remove('open');
document.querySelectorAll('.modal-overlay').forEach(o=>o.addEventListener('click',e=>{ if(e.target===o) o.classList.remove('open'); }));

function showToast(msg,type='success'){
  const t=document.getElementById('toast');
  t.textContent=(type==='success'?'✓  ':'✕  ')+msg;
  t.className=`toast show ${type}`;
  setTimeout(()=>t.classList.remove('show'),3500);
}
</script>
</body>
</html>
