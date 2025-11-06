<!doctype html>

<html lang="id">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Chronicles of Aetherion — Prototype</title>
  <style>
    /* Palette: biru, hijau, emas, gelap */
    :root{
      --bg:#081226; /* deep night */
      --panel:#0f2940;
      --muted:#98a8b9;
      --accent:#4db6ff; /* blue */
      --accent2:#78d6a3; /* green */
      --gold:#e9c46a; /* gold */
      --glass: rgba(255,255,255,0.04);
      --glass-2: rgba(255,255,255,0.02);
      --glass-border: rgba(255,255,255,0.06);
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;background:linear-gradient(180deg,var(--bg),#031020);color:#e6eef8}
    header{display:flex;align-items:center;gap:16px;padding:18px 22px;border-bottom:1px solid var(--glass-border);background:linear-gradient(0deg, rgba(255,255,255,0.02), transparent)}
    .logo{display:flex;align-items:center;gap:12px}
    .logo .symbol{width:48px;height:48px;border-radius:10px;background:linear-gradient(135deg,var(--accent),var(--accent2));display:flex;align-items:center;justify-content:center;box-shadow:0 6px 18px rgba(0,0,0,0.6)}
    .logo h1{font-size:18px;margin:0}
    nav{margin-left:auto;display:flex;gap:12px;align-items:center}
    .btn{background:var(--glass);border:1px solid var(--glass-border);padding:8px 12px;border-radius:10px;cursor:pointer}
    .btn.primary{background:linear-gradient(90deg,var(--accent),var(--accent2));color:#001019;border:none}
    main{display:grid;grid-template-columns:320px 1fr 360px;gap:18px;padding:18px}
    /* Side panels */
    .panel{background:linear-gradient(180deg,var(--panel),rgba(10,20,28,0.6));border-radius:12px;padding:14px;border:1px solid var(--glass-border);box-shadow:0 8px 30px rgba(2,6,12,0.7)}
    .left .search{display:flex;gap:8px;margin-bottom:10px}
    .search input{flex:1;padding:8px;border-radius:8px;border:1px solid var(--glass-border);background:transparent;color:var(--muted)}
    .class-list{display:flex;flex-direction:column;gap:8px}
    .class-card{display:flex;align-items:center;gap:10px;padding:10px;border-radius:10px;background:var(--glass);cursor:pointer;border:1px solid transparent}
    .class-card:hover{transform:translateY(-3px);transition:all .18s}
    .class-card.active{border-color:var(--gold);box-shadow:0 6px 18px rgba(233,196,106,0.08)}
    .class-icon{width:46px;height:46;border-radius:8px;background:linear-gradient(135deg,#0000 40%, rgba(255,255,255,0.03));display:flex;align-items:center;justify-content:center;font-weight:700}
    .stat-row{display:flex;gap:10px;flex-wrap:wrap;margin-top:10px}/* Center area */
.world{padding:16px;height:72vh;border-radius:12px;display:flex;flex-direction:column}
.world .toolbar{display:flex;gap:8px;align-items:center;margin-bottom:12px}
.cards{display:grid;grid-template-columns:repeat(auto-fill,minmax(220px,1fr));gap:12px;flex:1;overflow:auto;padding-bottom:8px}
.card{background:linear-gradient(180deg,rgba(255,255,255,0.02),transparent);padding:12px;border-radius:10px;border:1px solid var(--glass-border)}
.card h3{margin:0 0 6px 0}
.card p{margin:0;color:var(--muted);font-size:13px}

/* Right panel */
.right .section{margin-bottom:12px}
.skill-tree{display:flex;flex-direction:column;gap:8px}
.skill{padding:8px;border-radius:8px;border:1px dashed var(--glass-border);display:flex;justify-content:space-between;align-items:center}

footer{padding:12px;text-align:center;color:var(--muted);font-size:13px}

/* Responsive */
@media (max-width:1100px){main{grid-template-columns:1fr;padding:12px} .right{order:3} .left{order:2}}

  </style>
</head>
<body>
  <header>
    <div class="logo">
      <div class="symbol">✦</div>
      <div>
        <h1>Chronicles of Aetherion</h1>
        <div style="font-size:12px;color:var(--muted)">Prototype — UI & Gameplay mock</div>
      </div>
    </div>
    <nav>
      <button class="btn">Profile</button>
      <button class="btn">Guilds</button>
      <button class="btn">Store</button>
      <button class="btn primary" id="playBtn">Play (Demo)</button>
    </nav>
  </header>  <main>
    <aside class="left panel">
      <div class="search"><input id="search" placeholder="Cari quest, dungeon, item..."/></div><h3 style="margin:8px 0 6px 0">Karakter & Kelas</h3>
  <div class="class-list" id="classList">
    <!-- class cards injected by JS -->
  </div>

  <div style="margin-top:12px">
    <h4 style="margin:6px 0">Quick Stats</h4>
    <div class="stat-row" id="quickStats"></div>
  </div>

  <div style="margin-top:12px">
    <h4 style="margin:6px 0">Settings</h4>
    <div style="display:flex;gap:8px;flex-direction:column">
      <label><input type="checkbox" id="toggleParticles" checked/> Efek partikel</label>
      <label><input type="checkbox" id="toggleGlow" checked/> Efek cahaya</label>
      <label><input type="checkbox" id="toggleVsync"/> V-Sync</label>
    </div>
  </div>
</aside>

<section class="world panel">
  <div class="toolbar">
    <div style="font-weight:600">Dunia: Aetherion</div>
    <div style="margin-left:8px;color:var(--muted);font-size:13px">Mode: Demo (UI, battle mock, skill tree)</div>
    <div style="margin-left:auto;display:flex;gap:8px"><button class="btn" id="saveBtn">Save</button><button class="btn" id="loadBtn">Load</button></div>
  </div>

  <div class="cards" id="cards">
    <!-- cards: dungeons / quests / events -->
  </div>

  <div style="margin-top:10px;display:flex;gap:8px;align-items:center">
    <div style="font-size:13px;color:var(--muted)">Performance</div>
    <select id="perfSel" class="btn" style="margin-left:8px"><option>Low</option><option selected>Medium</option><option>High</option><option>Ultra</option></select>
    <div style="margin-left:auto;color:var(--muted);font-size:13px">Platform: Web UI (Unity/Unreal builds recommended)</div>
  </div>
</section>

<aside class="right panel">
  <div class="section">
    <h4 style="margin:6px 0">Selected Character</h4>
    <div id="selectedCard" style="padding:8px;border-radius:8px;background:var(--glass)">Belum ada karakter dipilih</div>
  </div>

  <div class="section">
    <h4 style="margin:6px 0">Skill Tree</h4>
    <div class="skill-tree" id="skillTree">
      <!-- skill nodes -->
    </div>
  </div>

  <div class="section">
    <h4 style="margin:6px 0">Guild & Sosial</h4>
    <div style="font-size:13px;color:var(--muted)">Chat Global: <span id="chatPreview">[Demo] Selamat datang, petualang!</span></div>
    <div style="margin-top:8px;display:flex;gap:8px"><input id="chatInput" placeholder="Kirim pesan..." style="flex:1;padding:8px;border-radius:8px;border:1px solid var(--glass-border);background:transparent;color:var(--muted)"/><button class="btn" id="sendChat">Kirim</button></div>
  </div>
</aside>

  </main>  <footer>Desain & fitur: demo UI — ini bukan game produksi. Engine: Unity/Unreal direkomendasikan untuk build akhir.</footer>  <script>
    // --- Demo data ---
    const CLASSES = [
      {id:'warrior',name:'Warrior',desc:'Spesialis pertarungan jarak dekat dan pertahanan.',hp:120,atk:18,def:14,icon:'🛡️'},
      {id:'mage',name:'Mage',desc:'Pengendali elemen dan sihir destruktif.',hp:78,atk:26,def:6,icon:'🔮'},
      {id:'rogue',name:'Rogue',desc:'Ahli serangan cepat dan kemampuan bersembunyi.',hp:92,atk:20,def:8,icon:'🗡️'},
    ];

    const DUNGEONS = [
      {id:'d1',title:'Gua Luminara',lvl:5,desc:'Dungeon penuh teka-teki dan cahaya mistik.'},
      {id:'d2',title:'Benteng Koral',lvl:12,desc:'Benteng tua dengan pasukan bandit.'},
      {id:'d3',title:'Reruntuhan Aether',lvl:20,desc:'Tempat artefak dan bahaya magis.'}
    ];

    // --- Render UI ---
    const classList = document.getElementById('classList');
    const quickStats = document.getElementById('quickStats');
    const cards = document.getElementById('cards');
    const selectedCard = document.getElementById('selectedCard');
    const skillTree = document.getElementById('skillTree');
    let activeClass = null;

    function mkClassCard(k){
      const el = document.createElement('div'); el.className='class-card'; el.dataset.id=k.id;
      el.innerHTML = `<div class='class-icon'>${k.icon}</div><div style='flex:1'><strong>${k.name}</strong><div style='font-size:13px;color:var(--muted)'>${k.desc}</div></div><div style='font-size:13px;color:var(--muted)'>Lv.1</div>`;
      el.addEventListener('click',()=>selectClass(k.id));
      return el;
    }

    function renderClasses(){
      classList.innerHTML='';
      CLASSES.forEach(c=>classList.appendChild(mkClassCard(c)));
    }

    function renderQuickStats(){
      quickStats.innerHTML='';
      const stats = [
        {k:'Gold',v:250}, {k:'Gems',v:12}, {k:'XP',v:1200}
      ];
      stats.forEach(s=>{
        const d=document.createElement('div'); d.style.padding='8px'; d.style.border='1px solid var(--glass-border)'; d.style.borderRadius='8px'; d.style.minWidth='80px'; d.innerHTML=`<div style='font-size:13px;color:var(--muted)'>${s.k}</div><div style='font-weight:700'>${s.v}</div>`;
        quickStats.appendChild(d);
      });
    }

    function mkDungeonCard(d){
      const el=document.createElement('div'); el.className='card';
      el.innerHTML=`<h3>${d.title} <small style='color:var(--muted);font-size:12px'>Lv ${d.lvl}</small></h3><p>${d.desc}</p><div style='margin-top:8px;display:flex;gap:8px'><button class='btn' onclick="startDungeon('${d.id}')">Jelajahi</button><button class='btn' onclick="viewDungeon('${d.id}')">Detail</button></div>`;
      return el;
    }

    function renderDungeons(){
      cards.innerHTML='';
      DUNGEONS.forEach(d=>cards.appendChild(mkDungeonCard(d)));
    }

    function selectClass(id){
      activeClass = CLASSES.find(c=>c.id===id);
      document.querySelectorAll('.class-card').forEach(el=>el.classList.toggle('active', el.dataset.id===id));
      selectedCard.innerHTML = `<div style='display:flex;gap:12px;align-items:center'><div style='font-size:32px'>${activeClass.icon}</div><div><div style='font-weight:700'>${activeClass.name}</div><div style='color:var(--muted);font-size:13px'>${activeClass.desc}</div><div style='margin-top:8px;color:var(--muted)'>HP ${activeClass.hp} • ATK ${activeClass.atk} • DEF ${activeClass.def}</div></div></div>`;
      buildSkillTree(activeClass.id);
    }

    function buildSkillTree(cid){
      // simple mock of skill tree based on class
      const skills = {
        warrior:[{id:'s1',n:'Perkuatan Dasar',d:'Tambahkan +6 DEF'},{id:'s2',n:'Serangan Putar',d:'AoE dekat'}],
        mage:[{id:'s1',n:'Kanal Energi',d:'Regenerasi mana'},{id:'s2',n:'Pelontar Petir',d:'Skill jarak jauh'}],
        rogue:[{id:'s1',n:'Bayangan',d:'Masuk stealth'},{id:'s2',n:'Serangan Balik',d:'Damage kritikal'}]
      };
      skillTree.innerHTML='';
      (skills[cid]||[]).forEach(s=>{
        const el=document.createElement('div'); el.className='skill'; el.innerHTML=`<div><strong>${s.n}</strong><div style='font-size:13px;color:var(--muted)'>${s.d}</div></div><button class='btn' onclick="unlockSkill('${s.id}')">Unlock</button>`;
        skillTree.appendChild(el);
      });
    }

    function unlockSkill(id){
      alert('Skill ' + id + ' di-unlock (demo)');
    }

    // --- Dungeon actions (demo) ---
    window.startDungeon = function(id){
      const d = DUNGEONS.find(x=>x.id===id);
      if(!activeClass){ alert('Pilih karakter terlebih dahulu!'); return; }
      // simple battle mockup
      const battleLog = [];
      let enemyHp = d.lvl * 20 + 60;
      let playerHp = activeClass.hp;
      battleLog.push(`Memulai pertempuran di ${d.title} — Musuh HP ${enemyHp}`);
      let turn=0;
      while(enemyHp>0 && playerHp>0 && turn<8){
        // player attack
        const dmg = Math.max(1, activeClass.atk + Math.floor(Math.random()*6) - Math.floor(Math.random()*4));
        enemyHp -= dmg; battleLog.push(`${activeClass.name} menyerang dan memberi ${dmg} dmg. Musuh HP: ${Math.max(0,enemyHp)}`);
        if(enemyHp<=0) break;
        // enemy attack
        const edmg = Math.max(1, Math.floor(d.lvl/2) + Math.floor(Math.random()*8));
        playerHp -= edmg; battleLog.push(`Musuh menyerang dan memberi ${edmg} dmg. ${activeClass.name} HP: ${Math.max(0,playerHp)}`);
        turn++;
      }
      const result = enemyHp<=0 ? 'Menang' : (playerHp<=0 ? 'Kalah' : 'Menyerah (batas demo)');
      battleLog.push('Hasil: ' + result);
      showModal('Battle Log — ' + d.title, battleLog.join('\n'));
    }

    window.viewDungeon = function(id){
      const d = DUNGEONS.find(x=>x.id===id);
      showModal(d.title, `${d.desc}\nLevel direkomendasikan: ${d.lvl}`);
    }

    // --- Modal ---
    function showModal(title,body){
      const wrapper = document.createElement('div'); wrapper.style.position='fixed'; wrapper.style.inset=0; wrapper.style.display='flex'; wrapper.style.alignItems='center'; wrapper.style.justifyContent='center'; wrapper.style.background='rgba(0,0,0,0.6)';
      const box = document.createElement('div'); box.style.width='min(720px,90vw)'; box.style.maxHeight='80vh'; box.style.overflow='auto'; box.style.background='#051427'; box.style.border='1px solid var(--glass-border)'; box.style.padding='18px'; box.style.borderRadius='10px';
      box.innerHTML = `<div style='display:flex;align-items:center;gap:12px'><h2 style='margin:0'>${title}</h2><div style='margin-left:auto'><button class='btn' id='closeModal'>Close</button></div></div><pre style='white-space:pre-wrap;color:var(--muted);margin-top:12px'>${body}</pre>`;wrapper.appendChild(box);
  document.body.appendChild(wrapper);
  document.getElementById('closeModal').addEventListener('click',()=>wrapper.remove());
}

// --- Chat demo ---
document.getElementById('sendChat').addEventListener('click',()=>{
  const txt = document.getElementById('chatInput').value.trim(); if(!txt) return;
  document.getElementById('chatPreview').textContent = txt;
  document.getElementById('chatInput').value='';
});

// --- Settings handlers ---
document.getElementById('toggleParticles').addEventListener('change',(e)=>{
  console.log('Particles:', e.target.checked);
});
document.getElementById('toggleGlow').addEventListener('change',(e)=>{
  console.log('Glow:', e.target.checked);
});

// Save / Load (local demo)
document.getElementById('saveBtn').addEventListener('click',()=>{
  const payload = {selected: activeClass?activeClass.id:null,perf:document.getElementById('perfSel').value};
  localStorage.setItem('aether_save', JSON.stringify(payload)); alert('Progress disimpan (local)');
});
document.getElementById('loadBtn').addEventListener('click',()=>{
  const s = localStorage.getItem('aether_save'); if(!s) return alert('Tidak ada save'); const p=JSON.parse(s); if(p.selected) selectClass(p.selected); document.getElementById('perfSel').value=p.perf; alert('Save dimuat');
});

// Play button demo
document.getElementById('playBtn').addEventListener('click',()=>{
  showModal('Demo Play', 'Mode demo: pilih karakter, lalu jelajahi dungeon untuk melihat pertempuran mock.');
});

// Init
renderClasses(); renderQuickStats(); renderDungeons();

// small accessibility: allow search filter
document.getElementById('search').addEventListener('input',(e)=>{
  const v=e.target.value.toLowerCase();
  // filter dungeons
  const filtered = DUNGEONS.filter(d=>d.title.toLowerCase().includes(v) || d.desc.toLowerCase().includes(v));
  cards.innerHTML=''; filtered.forEach(d=>cards.appendChild(mkDungeonCard(d)));
});

// expose some helpful functions for demo (window) already set for startDungeon/viewDungeon

  </script>
</body>
</html>
