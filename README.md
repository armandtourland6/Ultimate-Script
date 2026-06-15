[blox_fruits_full_ui_preview.html](https://github.com/user-attachments/files/28962406/blox_fruits_full_ui_preview.html)[Uploadi
<style>
*{box-sizing:border-box;margin:0;padding:0}
.win{width:580px;background:#0a0805;border-radius:10px;border:2px solid #c8a84b;overflow:hidden;font-family:'Inter','Segoe UI',sans-serif;margin:20px auto}
.titlebar{height:50px;background:#120e08;display:flex;align-items:center;padding:0 12px;gap:10px;border-bottom:1px solid #1e1a0f}
.logo{width:36px;height:36px;background:#0a0805;border-radius:7px;border:1px solid #c8a84b;display:flex;align-items:center;justify-content:center;font-size:18px;flex-shrink:0}
.title{color:#fff;font-size:12px;font-weight:700;letter-spacing:.4px;flex:1}
.closebtn{width:28px;height:28px;background:#0a0805;border-radius:6px;border:1px solid #2a2010;display:flex;align-items:center;justify-content:center;cursor:pointer;color:#fff;font-size:13px;font-weight:700}
.body{display:flex;height:390px}
.sidebar{width:148px;background:#0c0a05;padding:8px;display:flex;flex-direction:column;gap:4px;border-right:1px solid #1a1508;overflow-y:auto;flex-shrink:0}
.tab{padding:8px 10px;border-radius:6px;background:#141008;color:#b49b5a;font-size:10.5px;font-weight:600;cursor:pointer;transition:all .15s;user-select:none}
.tab.active{background:#c8a84b;color:#fff}
.tab:hover:not(.active){background:#1e1810;color:#d4b870}
.content{flex:1;overflow-y:auto;padding:8px 10px;display:flex;flex-direction:column;gap:7px}
.row{background:#120e08;border-radius:6px;padding:0 13px;height:42px;display:flex;align-items:center;justify-content:space-between;flex-shrink:0}
.row-tall{background:#120e08;border-radius:6px;padding:8px 13px;flex-shrink:0}
.label{color:#e0e0e0;font-size:10.5px;font-weight:600}
.label-muted{color:#c8a84b;font-size:10px;font-weight:600;margin-bottom:7px}
.sw{width:44px;height:23px;border-radius:12px;position:relative;cursor:pointer;transition:background .18s;flex-shrink:0}
.sw.on{background:#c8a84b}
.sw.off{background:#2e2920}
.knob{position:absolute;top:2.5px;width:18px;height:18px;background:#fff;border-radius:50%;transition:left .18s}
.sw.on .knob{left:calc(100% - 20.5px)}
.sw.off .knob{left:2.5px}
.cycle-btn{background:#c8a84b;color:#fff;font-size:10px;font-weight:700;padding:5px 11px;border-radius:6px;cursor:pointer;border:none;flex-shrink:0}
.action-btn{background:#1e1a0f;color:#c8a84b;font-size:10.5px;font-weight:700;padding:0 14px;height:36px;border-radius:6px;cursor:pointer;border:1px solid #c8a84b33;width:100%;text-align:left}
.action-btn:hover{background:#2a2410}
.track{height:6px;background:#282010;border-radius:3px;position:relative;margin-top:4px}
.fill{height:100%;background:#c8a84b;border-radius:3px;position:relative}
.fillknob{position:absolute;right:-6px;top:-5px;width:12px;height:12px;background:#fff;border-radius:50%}
.section-title{color:#c8a84b;font-size:9px;font-weight:700;letter-spacing:1.5px;padding:2px 0 0 2px;opacity:.7}
</style>

<div class="win">
  <div class="titlebar">
    <div class="logo">⚔️</div>
    <span class="title">🍎 BLOX FRUITS ULTIMATE V4 [GOD EDITION]</span>
    <div class="closebtn">✕</div>
  </div>
  <div class="body">
    <div class="sidebar" id="sidebar">
      <div class="tab active" data-tab="farm">🌾 Auto Farm</div>
      <div class="tab" data-tab="fruit">🍎 Devil Fruit</div>
      <div class="tab" data-tab="combat">⚔️ Combat</div>
      <div class="tab" data-tab="tp">🗺️ Teleport</div>
      <div class="tab" data-tab="events">🐉 Dojo & Events</div>
      <div class="tab" data-tab="stats">📊 Auto Stats</div>
      <div class="tab" data-tab="esp">👁️ ESP System</div>
      <div class="tab" data-tab="farmsp">💰 Farm Spécial</div>
      <div class="tab" data-tab="misc">⚙️ Settings/Misc</div>
    </div>

    <div class="content" id="content">

      <div class="page" id="page-farm">
        <div class="row"><span class="label">Auto Farm Level</span><div class="sw on"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Auto Quest</span><div class="sw off"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Bypass Fast Attack</span><div class="sw on"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Bring Mobs</span><div class="sw off"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Auto Buso Haki</span><div class="sw on"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Auto Ken Haki</span><div class="sw off"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Selected Weapon: Melee</span><button class="cycle-btn">Cycle ▶</button></div>
        <div class="row-tall"><div class="label-muted">AutoFarm Height (Y-Offset): 15</div><div class="track"><div class="fill" style="width:45%"><div class="fillknob"></div></div></div></div>
      </div>

      <div class="page" id="page-fruit" style="display:none">
        <div class="row"><span class="label">Notif. Spawn Fruit</span><div class="sw on"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Auto Collect Fruit</span><div class="sw off"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Fruit Sniper (TP instantané)</span><div class="sw on"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Afficher fruits actifs map</span><div class="sw off"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Priority Légendaire uniquement</span><div class="sw off"><div class="knob"></div></div></div>
      </div>

      <div class="page" id="page-combat" style="display:none">
        <div class="row"><span class="label">Kill Aura</span><div class="sw off"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Instakill</span><div class="sw off"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Auto Combo</span><div class="sw on"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Fly Attack</span><div class="sw off"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Anti-Ragdoll</span><div class="sw on"><div class="knob"></div></div></div>
        <div class="row-tall"><div class="label-muted">Kill Aura Range: 30</div><div class="track"><div class="fill" style="width:30%"><div class="fillknob"></div></div></div></div>
      </div>

      <div class="page" id="page-tp" style="display:none">
        <div class="section-title">SEA 1</div>
        <div class="row"><span class="label">Starter Island</span><button class="cycle-btn">TP ▶</button></div>
        <div class="row"><span class="label">Jungle / Pirate Village</span><button class="cycle-btn">TP ▶</button></div>
        <div class="row"><span class="label">Marine Fortress</span><button class="cycle-btn">TP ▶</button></div>
        <div class="section-title">SEA 2</div>
        <div class="row"><span class="label">Kingdom of Rose</span><button class="cycle-btn">TP ▶</button></div>
        <div class="row"><span class="label">Magma Village</span><button class="cycle-btn">TP ▶</button></div>
        <div class="section-title">SEA 3</div>
        <div class="row"><span class="label">Port Town</span><button class="cycle-btn">TP ▶</button></div>
        <div class="row"><span class="label">Mirage Island</span><button class="cycle-btn">TP ▶</button></div>
        <div class="row"><span class="label">TP vers Boss actif</span><button class="cycle-btn">TP ▶</button></div>
      </div>

      <div class="page" id="page-events" style="display:none">
        <div class="row"><span class="label">Claim Holiday Gifts</span><div class="sw off"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Store Holiday Gifts</span><div class="sw off"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Auto Claim Dojo Quest</span><div class="sw on"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Run White Belt Quest</span><div class="sw off"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Run Purple Belt Boss Quest</span><div class="sw off"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Kill Hydra + Collect Ember</span><div class="sw off"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Auto Upgrade Dragon Talon</span><div class="sw off"><div class="knob"></div></div></div>
      </div>

      <div class="page" id="page-stats" style="display:none">
        <div class="row"><span class="label">Auto Upgrade Melee (+)</span><div class="sw on"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Auto Upgrade Defense (+)</span><div class="sw off"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Auto Upgrade Sword (+)</span><div class="sw off"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Auto Upgrade Gun (+)</span><div class="sw off"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Auto Upgrade Devil Fruit (+)</span><div class="sw on"><div class="knob"></div></div></div>
      </div>

      <div class="page" id="page-esp" style="display:none">
        <div class="row"><span class="label">Player ESP</span><div class="sw on"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Chest ESP</span><div class="sw off"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Devil Fruit ESP</span><div class="sw on"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Island ESP</span><div class="sw off"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Mob ESP</span><div class="sw on"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Flower ESP (Red/Blue)</span><div class="sw off"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Fruit Spawner ESP</span><div class="sw on"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Mirage Island ESP</span><div class="sw off"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Legendary Sword Dealer ESP</span><div class="sw off"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Master of Aura ESP</span><div class="sw off"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Advanced Fruit Dealer ESP</span><div class="sw off"><div class="knob"></div></div></div>
      </div>

      <div class="page" id="page-farmsp" style="display:none">
        <div class="row"><span class="label">Auto Raid</span><div class="sw off"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Auto Coffre</span><div class="sw off"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Auto Mastery Arme</span><div class="sw on"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Auto Mastery Fruit</span><div class="sw off"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Farm Matériaux</span><div class="sw off"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Auto Event</span><div class="sw off"><div class="knob"></div></div></div>
      </div>

      <div class="page" id="page-misc" style="display:none">
        <div class="row"><span class="label">Speed Hack</span><div class="sw off"><div class="knob"></div></div></div>
        <div class="row-tall"><div class="label-muted">Custom Speed: 26</div><div class="track"><div class="fill" style="width:15%"><div class="fillknob"></div></div></div></div>
        <div class="row"><span class="label">Infinite Jump</span><div class="sw on"><div class="knob"></div></div></div>
        <div class="row"><span class="label">NoClip</span><div class="sw off"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Anti-AFK Permanent</span><div class="sw on"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Infinite Stamina/Energy</span><div class="sw off"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Bypass Dodge Cooldown</span><div class="sw off"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Mute Audio/Sound</span><div class="sw off"><div class="knob"></div></div></div>
        <div class="row"><span class="label">Hide Notifications</span><div class="sw off"><div class="knob"></div></div></div>
        <button class="action-btn">⚡ Optimiser FPS (Boost Graphics)</button>
        <button class="action-btn">🔀 Server Hop (moins de joueurs)</button>
        <button class="action-btn">🔄 Rejoin Current Server</button>
      </div>

    </div>
  </div>
</div>

<script>
document.querySelectorAll('.sw').forEach(sw=>{
  sw.addEventListener('click',()=>{
    sw.classList.toggle('on');
    sw.classList.toggle('off');
  });
});
document.querySelectorAll('.tab').forEach(tab=>{
  tab.addEventListener('click',()=>{
    document.querySelectorAll('.tab').forEach(t=>t.classList.remove('active'));
    document.querySelectorAll('.page').forEach(p=>p.style.display='none');
    tab.classList.add('active');
    document.getElementById('page-'+tab.dataset.tab).style.display='flex';
    document.getElementById('page-'+tab.dataset.tab).style.flexDirection='column';
    document.getElementById('page-'+tab.dataset.tab).style.gap='7px';
  });
});
document.querySelectorAll('.cycle-btn').forEach(b=>{
  const opts=['Melee','Sword','Devil Fruit'];
  let i=0;
  b.addEventListener('click',()=>{i=(i+1)%opts.length;const l=b.parentElement.querySelector('.label');if(l&&l.textContent.includes(':'))l.textContent=l.textContent.replace(/: .*/,': '+opts[i]);});
});
</script>
ng blox_fruits_full_ui_preview.html…]()

//-------to launch it just use-------\\
loadstring(game:HttpGet("https://raw.githubusercontent.com/armandtourland6/Ultimate-Script/main/ultimatescript.lua"))() 
