<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Método Colutta</title>
<meta name="version" content="v9-20260501">
<meta http-equiv="Cache-Control" content="no-cache, no-store, must-revalidate">
<meta http-equiv="Pragma" content="no-cache">
<meta http-equiv="Expires" content="0">
<link rel="manifest" href="/manifest.json">
<meta name="theme-color" content="#0d1b2e">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-title" content="Colutta">
<link rel="apple-touch-icon" href="/icons/icon-192.png">
<style>
  @import url('https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;1,300;1,400&family=Barlow+Condensed:wght@300;400;500;600;700&display=swap');
  :root{--navy:#0d1b2e;--navy-mid:#162440;--navy-lt:#1e3055;--gold:#c9a84c;--gold-lt:#e8c97a;--white:#f0ece3;--dim:rgba(240,236,227,0.5);--faint:rgba(240,236,227,0.07);--success:#4a8a5a;--danger:#8a4a4a;}
  *{margin:0;padding:0;box-sizing:border-box;}
  body{background:var(--navy);color:var(--white);font-family:'Barlow Condensed',sans-serif;min-height:100vh;}
  .topbar{background:var(--navy-mid);border-bottom:1px solid rgba(201,168,76,0.2);padding:12px 20px;display:flex;align-items:center;justify-content:space-between;position:sticky;top:0;z-index:100;}
  .brand{font-family:'Cormorant Garamond',serif;font-size:18px;font-weight:600;font-style:italic;color:var(--gold-lt);}
  .brand-role{font-style:normal;font-weight:300;color:var(--dim);font-size:12px;margin-left:8px;letter-spacing:2px;}
  .btn{font-family:'Barlow Condensed',sans-serif;font-size:10px;font-weight:700;letter-spacing:2px;text-transform:uppercase;padding:9px 16px;border-radius:3px;cursor:pointer;border:1px solid;transition:all .2s;display:inline-flex;align-items:center;gap:6px;}
  .btn-primary{background:var(--gold);color:var(--navy);border-color:var(--gold);}
  .btn-primary:hover{background:var(--gold-lt);}
  .btn-secondary{background:transparent;color:var(--dim);border-color:rgba(240,236,227,0.2);}
  .btn-secondary:hover{color:var(--white);}
  .btn-success{background:var(--success);color:var(--white);border-color:var(--success);}
  .btn-ghost{background:transparent;border-color:transparent;color:var(--dim);padding:5px 8px;}
  .btn-ghost:hover{color:var(--white);background:var(--faint);}
  .btn-sm{padding:5px 10px;font-size:9px;}
  .card{background:var(--navy-mid);border:1px solid rgba(240,236,227,0.08);border-radius:4px;padding:18px 20px;}
  .card+.card{margin-top:10px;}
  .card-lbl{font-size:10px;letter-spacing:3px;color:var(--gold);text-transform:uppercase;margin-bottom:12px;}
  .fg{display:flex;flex-direction:column;gap:5px;}
  .fl{font-size:10px;letter-spacing:2px;color:var(--dim);text-transform:uppercase;}
  .fi,.fs{background:var(--navy-lt);border:1px solid rgba(240,236,227,0.12);border-radius:3px;padding:8px 11px;color:var(--white);font-family:'Barlow Condensed',sans-serif;font-size:13px;outline:none;transition:border-color .2s;width:100%;}
  .fi:focus,.fs:focus{border-color:var(--gold);}
  .fs option{background:var(--navy-mid);}
  .fgrid{display:grid;grid-template-columns:repeat(auto-fill,minmax(160px,1fr));gap:12px;}
  .ftextarea{background:var(--navy-lt);border:1px solid rgba(240,236,227,0.12);border-radius:3px;padding:8px 11px;color:var(--white);font-family:'Barlow Condensed',sans-serif;font-size:13px;outline:none;width:100%;resize:vertical;min-height:70px;}
  .ftextarea:focus{border-color:var(--gold);}
  .view{display:none;padding:24px 20px;max-width:960px;margin:0 auto;}
  .view.active{display:block;}
  .login-wrap{min-height:100vh;display:flex;align-items:center;justify-content:center;padding:20px;}
  .login-box{background:var(--navy-mid);border:1px solid rgba(201,168,76,0.2);border-radius:4px;padding:36px 32px;width:100%;max-width:380px;text-align:center;}
  .login-title{font-family:'Cormorant Garamond',serif;font-size:32px;font-weight:300;margin-bottom:6px;}
  .login-title em{font-style:italic;color:var(--gold-lt);}
  .login-sub{font-size:11px;letter-spacing:3px;color:var(--dim);text-transform:uppercase;margin-bottom:28px;}
  .athlete-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(260px,1fr));gap:10px;}
  .athlete-card{background:var(--navy-mid);border:1px solid rgba(240,236,227,0.08);border-radius:4px;padding:16px 18px;cursor:pointer;transition:all .2s;}
  .athlete-card:hover{background:var(--navy-lt);border-color:rgba(201,168,76,0.3);}
  .athlete-name{font-size:16px;font-weight:600;margin-bottom:4px;}
  .athlete-meta{font-size:11px;color:var(--dim);}
  .athlete-badge{display:inline-block;font-size:9px;font-weight:700;letter-spacing:2px;text-transform:uppercase;padding:2px 7px;border-radius:2px;border:1px solid;margin-top:6px;}
  .section-title{font-family:'Cormorant Garamond',serif;font-size:24px;font-weight:300;margin-bottom:4px;}
  .section-title em{font-style:italic;color:var(--gold-lt);}
  .section-sub{font-size:11px;letter-spacing:2px;color:var(--dim);text-transform:uppercase;margin-bottom:20px;}
  .ath-bar{display:flex;gap:14px;flex-wrap:wrap;padding:11px 16px;background:rgba(201,168,76,0.06);border:1px solid rgba(201,168,76,0.15);border-radius:3px;margin-bottom:18px;}
  .ath-item{display:flex;flex-direction:column;gap:1px;}
  .ath-lbl{font-size:9px;letter-spacing:2px;color:var(--dim);text-transform:uppercase;}
  .ath-val{font-size:13px;font-weight:600;}
  .day-card{background:var(--navy-mid);border:1px solid rgba(240,236,227,0.08);border-radius:4px;margin-bottom:10px;overflow:hidden;}
  .day-header{padding:12px 16px;display:flex;align-items:center;gap:10px;border-bottom:1px solid rgba(240,236,227,0.06);background:rgba(240,236,227,0.03);}
  .day-num{width:28px;height:28px;border-radius:50%;background:var(--gold);color:var(--navy);display:flex;align-items:center;justify-content:center;font-size:12px;font-weight:700;flex-shrink:0;}
  .day-name{font-size:14px;font-weight:600;flex:1;}
  .day-desc{font-size:11px;color:var(--dim);}
  .block{border-left:3px solid;margin:8px 14px;border-radius:0 3px 3px 0;background:var(--faint);overflow:hidden;}
  .block-header{padding:9px 12px;display:flex;align-items:center;gap:8px;cursor:pointer;user-select:none;}
  .block-badge{font-size:8px;font-weight:700;letter-spacing:2px;text-transform:uppercase;padding:2px 7px;border-radius:2px;border:1px solid;white-space:nowrap;flex-shrink:0;}
  .block-type-lbl{font-size:11px;color:var(--dim);flex:1;}
  .block-chevron{font-size:11px;color:var(--dim);transition:transform .2s;margin-left:auto;}
  .block.open .block-chevron{transform:rotate(180deg);}
  .block-body{display:none;padding:0 12px 10px;}
  .block.open .block-body{display:block;}
  .ex-row{display:grid;grid-template-columns:1fr 1fr auto;gap:7px;margin-bottom:7px;align-items:end;}
  .ex-mini-group{display:flex;flex-direction:column;gap:3px;}
  .ex-mini-lbl{font-size:8px;letter-spacing:1px;color:var(--dim);text-transform:uppercase;}
  .ex-sel,.ex-inp,.ex-mini{background:var(--navy-lt);border:1px solid rgba(240,236,227,0.12);border-radius:3px;padding:6px 9px;color:var(--white);font-family:'Barlow Condensed',sans-serif;font-size:11px;outline:none;width:100%;}
  .ex-sel:focus,.ex-inp:focus,.ex-mini:focus{border-color:var(--gold);}
  .ex-sel option{background:var(--navy-mid);}
  .ex-inp::placeholder{color:var(--dim);}
  .block-actions{display:flex;gap:6px;padding-top:6px;border-top:1px solid rgba(240,236,227,0.05);margin-top:6px;flex-wrap:wrap;}
  .add-block-row{margin:6px 14px 12px;display:flex;gap:6px;}
  .ipill{display:inline-flex;align-items:center;font-size:10px;font-weight:700;letter-spacing:1px;padding:3px 8px;border-radius:2px;border:1px solid;text-transform:uppercase;margin-right:6px;margin-bottom:4px;}
  .athlete-view{padding:20px 16px;max-width:720px;margin:0 auto;}
  .week-badge{display:inline-flex;align-items:center;gap:8px;padding:6px 14px;border-radius:3px;border:1px solid rgba(201,168,76,0.3);background:rgba(201,168,76,0.08);font-size:11px;font-weight:700;letter-spacing:2px;text-transform:uppercase;color:var(--gold);margin-bottom:20px;}
  .registro-card{background:var(--navy-mid);border:1px solid rgba(240,236,227,0.08);border-radius:4px;margin-bottom:8px;overflow:hidden;}
  .reg-header{padding:10px 14px;display:flex;align-items:center;gap:8px;cursor:pointer;user-select:none;}
  .reg-ex-name{font-size:13px;font-weight:600;flex:1;}
  .reg-body{display:none;padding:0 14px 12px;}
  .reg-body.open{display:block;}
  .reg-grid{display:grid;grid-template-columns:1fr 1fr;gap:8px;margin-bottom:8px;}
  .feedback-box{background:rgba(201,168,76,0.06);border:1px solid rgba(201,168,76,0.2);border-radius:3px;padding:10px 12px;margin-top:8px;}
  .feedback-label{font-size:9px;letter-spacing:2px;color:var(--gold);text-transform:uppercase;margin-bottom:5px;}
  .feedback-text{font-size:12px;color:var(--white);line-height:1.6;}
  .saved-indicator{display:none;font-size:10px;letter-spacing:1px;color:var(--success);text-transform:uppercase;font-weight:700;}
  .saved-indicator.show{display:inline;}
  .feedback-panel{background:var(--navy-mid);border:1px solid rgba(240,236,227,0.08);border-radius:4px;margin-bottom:10px;padding:16px 18px;}
  .fp-athlete{font-size:14px;font-weight:600;margin-bottom:4px;}
  .fp-meta{font-size:11px;color:var(--dim);margin-bottom:10px;}
  .fp-comment{background:rgba(240,236,227,0.05);border-radius:3px;padding:10px 12px;font-size:12px;color:var(--white);line-height:1.6;margin-bottom:8px;border-left:3px solid rgba(201,168,76,0.4);}
  .fp-reply-area{display:flex;gap:8px;margin-top:8px;}
  .modal-overlay{position:fixed;inset:0;background:rgba(0,0,0,0.7);z-index:500;display:none;align-items:center;justify-content:center;padding:20px;}
  .modal-overlay.open{display:flex;}
  .modal{background:var(--navy-mid);border:1px solid rgba(201,168,76,0.25);border-radius:4px;padding:22px;width:100%;max-width:400px;}
  .modal-title{font-size:15px;font-weight:600;margin-bottom:14px;color:var(--gold-lt);}
  .link-box{background:var(--navy);border:1px solid rgba(240,236,227,0.1);border-radius:3px;padding:10px 14px;font-family:monospace;font-size:11px;color:var(--gold);word-break:break-all;margin:10px 0;}
  .tabs{display:flex;gap:0;border-bottom:1px solid rgba(240,236,227,0.08);margin-bottom:20px;}
  .tab-btn{padding:10px 18px;font-size:10px;font-weight:700;letter-spacing:2px;text-transform:uppercase;color:var(--dim);border-bottom:2px solid transparent;cursor:pointer;transition:all .2s;user-select:none;background:none;border-top:none;border-left:none;border-right:none;}
  .tab-btn.active{color:var(--gold);border-bottom-color:var(--gold);}
  .notif-dot{width:7px;height:7px;border-radius:50%;background:#e05050;display:inline-block;margin-left:4px;vertical-align:middle;}
  .empty{text-align:center;padding:40px 20px;color:var(--dim);font-size:13px;letter-spacing:1px;}
  @media(max-width:600px){.view,.athlete-view{padding:16px 12px;}.athlete-grid{grid-template-columns:1fr;}.ex-row{grid-template-columns:1fr;}.reg-grid{grid-template-columns:1fr;}.fgrid{grid-template-columns:1fr 1fr;}}
</style>
</head>
<body>

<div id="login-screen" class="login-wrap">
  <div class="login-box">
    <div class="login-title">Método <em>Colutta</em></div>
    <div class="login-sub">Sistema de entrenamiento</div>
    <div style="display:flex;flex-direction:column;gap:12px;">
      <button class="btn btn-primary" style="width:100%;justify-content:center;font-size:12px;padding:13px;" onclick="loginCoach()">Ingresar como entrenador</button>
      <div style="font-size:11px;color:var(--dim);text-align:center;letter-spacing:1px;">— o —</div>
      <div class="fg"><label class="fl">Código de atleta</label><input class="fi" id="athlete-token-input" type="text" placeholder="Tu código personal..."></div>
      <button class="btn btn-secondary" style="width:100%;justify-content:center;" onclick="loginAthlete()">Ver mi plan</button>
    </div>
  </div>
</div>

<div class="topbar" id="topbar" style="display:none">
  <div class="brand">Método Colutta <span class="brand-role" id="role-label"></span></div>
  <div style="display:flex;gap:8px;align-items:center;">
    <span id="notif-count" style="font-size:10px;color:var(--gold);letter-spacing:1px;display:none;"></span>
    <button class="btn btn-ghost btn-sm" onclick="logout()">Salir</button>
  </div>
</div>

<div id="coach-app" style="display:none">
  <div style="background:var(--navy-mid);border-bottom:1px solid rgba(240,236,227,0.06);padding:0 20px;">
    <div style="max-width:960px;margin:0 auto;display:flex;">
      <button class="tab-btn active" onclick="coachTab('atletas')">Atletas</button>
      <button class="tab-btn" onclick="coachTab('nuevo-plan')">Nuevo plan</button>
      <button class="tab-btn" onclick="coachTab('feedback')">Feedback <span id="feedback-dot" style="display:none" class="notif-dot"></span></button>
    </div>
  </div>

  <div class="view active" id="view-atletas">
    <div style="display:flex;justify-content:space-between;align-items:baseline;margin-bottom:20px;flex-wrap:wrap;gap:10px;">
      <div><div class="section-title">Tus <em>Atletas</em></div><div class="section-sub">Seleccioná para ver planes y registros</div></div>
      <button class="btn btn-primary" onclick="openNewAthleteModal()">+ Nuevo atleta</button>
    </div>
    <div id="athletes-list" class="athlete-grid"><div class="empty">Cargando...</div></div>
  </div>

  <div class="view" id="view-nuevo-plan">
    <div class="section-title">Nuevo <em>Plan</em></div>
    <div class="section-sub">Diseñá el plan · se guarda en Supabase</div>
    <div class="card" style="margin-bottom:12px;">
      <div class="card-lbl">Atleta y configuración</div>
      <div class="fgrid">
        <div class="fg"><label class="fl">Atleta</label><select class="fs" id="np-atleta" onchange="onAthleteChange()"></select></div>
        <div class="fg"><label class="fl">Fase</label><select class="fs" id="np-fase" onchange="updateIntPreview()"><option value="F1">F1 — Ordenar</option><option value="F2">F2 — Construir</option><option value="F3">F3 — Intensificar</option><option value="F4">F4 — Consolidar</option></select></div>
        <div class="fg"><label class="fl">Microciclo</label><select class="fs" id="np-micro" onchange="updateIntPreview()"><option value="1">Sem 1–2</option><option value="2">Sem 3–4</option><option value="3">Sem 5–6</option><option value="4">Sem 7–8</option></select></div>
        <div class="fg"><label class="fl">Semana</label><select class="fs" id="np-semana" onchange="updateIntPreview()"><option value="A">A — Instalar</option><option value="B">B — Responder</option></select></div>
      </div>
    </div>
    <div class="card" style="margin-bottom:12px;"><div class="card-lbl">Intensidad prescripta</div><div id="np-int-preview"></div></div>

    <div class="card" style="margin-bottom:12px;" id="variant-selector-card">
      <div class="card-lbl">Variante de distribución</div>
      <div id="variant-options" style="display:flex;flex-direction:column;gap:6px;"></div>
    </div>

    <div id="custom-day-controls" style="display:none;margin-bottom:12px;">
      <div class="card">
        <div class="card-lbl">Estructura personalizada</div>
        <div style="display:flex;gap:10px;align-items:flex-end;flex-wrap:wrap;">
          <div class="fg" style="flex:0 0 140px">
            <label class="fl">Días de la semana</label>
            <input class="fi" type="number" min="1" max="7" id="custom-days-count" value="4" style="text-align:center">
          </div>
          <button class="btn btn-secondary" onclick="initCustomDays()">Generar días vacíos</button>
        </div>
      </div>
    </div>

    <div id="np-days"></div>
    <div style="display:flex;gap:8px;margin-top:16px;flex-wrap:wrap;">
      <button class="btn btn-primary" onclick="savePlan()">💾 Guardar plan</button>
      <button class="btn btn-secondary" onclick="coachTab('atletas')">Cancelar</button>
    </div>
  </div>

  <div class="view" id="view-feedback">
    <div class="section-title">Feed<em>back</em></div>
    <div class="section-sub">Registros recientes · respondé con comentarios</div>
    <div id="feedback-list"><div class="empty">Cargando...</div></div>
  </div>

  <div class="view" id="view-atleta-detail">
    <div style="display:flex;align-items:center;gap:10px;margin-bottom:16px;">
      <button class="btn btn-ghost" onclick="coachTab('atletas')">← Volver</button>
      <div id="detail-title" class="section-title" style="margin-bottom:0"></div>
    </div>
    <div id="atleta-detail-content"></div>
  </div>
</div>

<div id="athlete-app" style="display:none">
  <div class="athlete-view"><div id="athlete-content"><div class="empty">Cargando tu plan...</div></div></div>
</div>

<div class="modal-overlay" id="modal-new-athlete">
  <div class="modal">
    <div class="modal-title">Nuevo atleta</div>
    <div style="display:flex;flex-direction:column;gap:10px;margin-bottom:16px;">
      <div class="fg"><label class="fl">Nombre *</label><input class="fi" id="na-nombre" type="text" placeholder="Nombre completo"></div>
      <div class="fg"><label class="fl">Email (opcional)</label><input class="fi" id="na-email" type="email"></div>
      <div class="fg"><label class="fl">Días por semana</label><select class="fs" id="na-dias"><option value="1">1 día</option><option value="2">2 días</option><option value="3">3 días</option><option value="4" selected>4 días</option><option value="5">5 días</option></select></div>
      <div class="fg"><label class="fl">Notas</label><textarea class="ftextarea" id="na-notas" placeholder="Objetivo, historial, limitaciones..."></textarea></div>
    </div>
    <div style="display:flex;gap:8px;">
      <button class="btn btn-primary" onclick="saveNewAthlete()">Crear atleta</button>
      <button class="btn btn-secondary" onclick="closeModal('modal-new-athlete')">Cancelar</button>
    </div>
  </div>
</div>

<div class="modal-overlay" id="modal-edit-athlete">
  <div class="modal">
    <div class="modal-title">Editar atleta</div>
    <input type="hidden" id="ea-id">
    <div style="display:flex;flex-direction:column;gap:10px;margin-bottom:16px;">
      <div class="fg"><label class="fl">Nombre *</label><input class="fi" id="ea-nombre" type="text"></div>
      <div class="fg"><label class="fl">Email</label><input class="fi" id="ea-email" type="email"></div>
      <div class="fg"><label class="fl">Días por semana</label>
        <select class="fs" id="ea-dias">
          <option value="1">1 día</option>
          <option value="1">1 día</option>
          <option value="2">2 días</option>
          <option value="3">3 días</option>
          <option value="4">4 días</option>
          <option value="5">5 días</option>
        </select>
      </div>
      <div class="fg"><label class="fl">Notas</label><textarea class="ftextarea" id="ea-notas" placeholder="Objetivo, historial, limitaciones..."></textarea></div>
    </div>
    <div style="display:flex;gap:8px;">
      <button class="btn btn-primary" onclick="saveEditAthlete()">Guardar cambios</button>
      <button class="btn btn-secondary" onclick="closeModal('modal-edit-athlete')">Cancelar</button>
    </div>
  </div>
</div>

<div class="modal-overlay" id="modal-share">
  <div class="modal">
    <div class="modal-title">Link del atleta</div>
    <div style="font-size:12px;color:var(--dim);margin-bottom:8px;">Compartí este link. El atleta lo abre y ve su plan.</div>
    <div class="link-box" id="share-link-text"></div>
    <div style="display:flex;gap:8px;">
      <button class="btn btn-primary" onclick="copyShareLink()">📋 Copiar</button>
      <button class="btn btn-secondary" onclick="closeModal('modal-share')">Cerrar</button>
    </div>
  </div>
</div>

<script>
const SB_URL = "https://teccrnbqltlscatxdyam.supabase.co";
const SB_KEY = "sb_publishable_Ui02rP6M59QLPvAv0YB9Cg_iFdK-IcP";

async function sb(path, method="GET", body=null){
  const headers={"Content-Type":"application/json","apikey":SB_KEY,"Authorization":"Bearer "+SB_KEY};
  if(method==="POST") headers["Prefer"]="return=representation";
  if(method==="PATCH"||method==="DELETE") headers["Prefer"]="return=minimal";
  const opts={method,headers};
  if(body) opts.body=JSON.stringify(body);
  const res=await fetch(SB_URL+"/rest/v1/"+path,opts);
  if(!res.ok){const e=await res.text();throw new Error(e);}
  const t=await res.text();return t?JSON.parse(t):[];
}

const PC={bisagra:"#c9a84c",sentadilla:"#4a7fa5",empuje:"#5b9e8a",traccion:"#a57060",core:"#7a6aaa",cargada:"#5a8a6a",accesorio:"#607080"};
const PHASE_COLORS={F1:"#4a7fa5",F2:"#5b9e8a",F3:"#c9a84c",F4:"#a57060"};
const PHASE_LABELS={F1:"Ordenar",F2:"Construir",F3:"Intensificar",F4:"Consolidar"};

const INT={
  F1:{1:{A:{s:3,r:"8",rpe:"RPE 6-7",rir:"RIR 3-4",note:"Técnica prioritaria"},B:{s:3,r:"8",rpe:"RPE 7",rir:"RIR 3",note:""}},2:{A:{s:3,r:"8",rpe:"RPE 7",rir:"RIR 2-3",note:""},B:{s:4,r:"6",rpe:"RPE 7-8",rir:"RIR 2",note:""}},3:{A:{s:4,r:"6",rpe:"RPE 7-8",rir:"RIR 2",note:""},B:{s:4,r:"6",rpe:"RPE 8",rir:"RIR 1-2",note:""}},4:{A:{s:4,r:"6",rpe:"RPE 8",rir:"RIR 1-2",note:"Cierre F1"},B:{s:4,r:"6",rpe:"RPE 8",rir:"RIR 1",note:""}}},
  F2:{1:{A:{s:4,r:"8",rpe:"RPE 7-8",rir:"RIR 2-3",note:""},B:{s:4,r:"8",rpe:"RPE 8",rir:"RIR 2",note:""}},2:{A:{s:4,r:"6",rpe:"RPE 8",rir:"RIR 1-2",note:"Tempo"},B:{s:4,r:"6",rpe:"RPE 8-9",rir:"RIR 1",note:""}},3:{A:{s:5,r:"6",rpe:"RPE 8-9",rir:"RIR 1",note:"ISO holds"},B:{s:5,r:"5",rpe:"RPE 8-9",rir:"RIR 0-1",note:""}},4:{A:{s:5,r:"5",rpe:"RPE 9",rir:"RIR 0-1",note:"Cierre F2"},B:{s:5,r:"4",rpe:"RPE 9",rir:"RIR 0",note:""}}},
  F3:{1:{A:{s:4,r:"6",rpe:"RPE 8-9",rir:"RIR 1-2",note:"Entrada F3"},B:{s:4,r:"6",rpe:"RPE 9",rir:"RIR 0-1",note:""}},2:{A:{s:5,r:"5",rpe:"RPE 9",rir:"RIR 0-1",note:"Rest-pause"},B:{s:5,r:"4",rpe:"RPE 9-10",rir:"RIR 0",note:""}},3:{A:{s:5,r:"ME",rpe:"RPE 10",rir:"RIR 0",note:"Pico volumen"},B:{s:5,r:"ME",rpe:"RPE 10",rir:"RIR 0",note:"Dropset"}},4:{A:{s:4,r:"3",rpe:"RPE 10",rir:"RIR 0",note:"Pico intensidad"},B:{s:4,r:"3",rpe:"RPE 10",rir:"RIR 0",note:""}}},
  F4:{1:{A:{s:4,r:"6",rpe:"RPE 8-9",rir:"RIR 0-1",note:"Consolidación"},B:{s:4,r:"6",rpe:"RPE 9",rir:"RIR 0",note:""}},2:{A:{s:4,r:"8",rpe:"RPE 8",rir:"RIR 0-1",note:""},B:{s:4,r:"8",rpe:"RPE 8-9",rir:"RIR 0",note:""}},3:{A:{s:3,r:"10",rpe:"RPE 8",rir:"RIR 1",note:"Integración"},B:{s:3,r:"10",rpe:"RPE 8",rir:"RIR 0-1",note:""}}}
};

const EX={
  core:["Plancha baja","Plancha baja con carga","Body saw","W. body saw","Knees to elbows (K2E)","KB around the body","Dual KB front rack marches","Rotaciones de tronco en polea","ISO Pallof press con banda","Abdominales con rueda","KB TGU","KB bottom up TGU","Hollow hold","Inclinaciones laterales con carga","Caminata de granjero con KB OH","Tall kneeling KB halo","Giros rusos con carga","Crunch lateral","Abdominales rectos cortos","Abdominales rectos largos con carga","Dragon flag","Marcha de granjero estática con MC","Bear wall plank","Plancha frontal con pelota","Superfish","KB suitcase farmer march","Rotaciones de tronco con banda","Plank get up","Bird dog ISO","Dead hang","V ups","Sit ups"],
  bisagra:["Peso muerto con barra","Peso muerto sumo con barra","Peso muerto rumano con barra","Tempo peso muerto rumano con barra","Peso muerto rumano con MC a una pierna","Peso muerto a una pierna con barra","Hip thrust con barra","BB hip thrust + ISO hold","Puente de glúteos con barra","Puente de glúteos a una pierna","Buenos días con barra","Extensión de cadera en banco romano","Extensión de cadera en banco romano con carga","KB Russian swing","KB swing americano","KB swing to goblet squat","SDHP con KB","Flexión de rodillas en máquina","Flexión de rodillas en máquina a una pierna","Nordic curl","Reverse nordic curl","BB kang squat","Granjereo con KB"],
  sentadilla:["Sentadilla frontal con barra","Sentadilla trasera con barra","Tempo sentadilla frontal (3-1-2)","Sentadilla zombie con barra","Sentadilla en multipower","Sentadilla copa con MC/KB","Sentadilla copa con salto","Bulgarian split squat con MC","Sentadilla búlgara carga contralateral","Estocadas estáticas con barra","Estocadas estáticas con MC","Estocadas caminando con MC","Estocada con salto","Estocada isométrica","Box step up alt con MC","Subida al banco carga contralateral","Walking lunges","Prensa 45°","Extensión de rodillas en máquina","Extensión de rodillas a una pierna","Wall sit","ISO squat","Sissy squat","BB front squat","BB OH squat","Box jump","Broad jump"],
  empuje:["Empuje de pecho con barra en banco plano","Floor press con barra","Empuje de pecho con barra en banco inclinado","Empuje de pecho con MC en banco inclinado","Empuje de pecho con MC en banco plano","Press militar con barra","BB push press","Push press con barra","Empuje de hombros con MC sentado","Press de hombro en landmine","Fondos en paralelas","Fondos en paralelas con carga","Hindu push ups","Push ups","Push ups diamante","Box pike push up","Pike push ups","Thrusters con MC","Apertura de pecho en máquina","Cruces en polea"],
  traccion:["Dominadas agarre prono","Dominadas agarre supino","Dominadas con carga","Tracción en dorsalera agarre prono","Tracción en dorsalera agarre supino","Tracción en dorsalera amplio","Tracción en dorsalera a un brazo","Remo con barra agarre prono","Remo con barra agarre supino","Remo en landmine","Landmine meadow row","Pendlay row","Remo a un brazo con MC","Remo serrucho a un brazo","Remo helms con MC","Remos australianos","Ring rows","Remo al mentón en polea","Pullover con MC","Pullover a un brazo en polea","Facepull en polea con soga","Vuelos laterales con MC","Vuelos posteriores con MC","Vuelos frontales con disco","Patada de glúteo en máquina","Patada sprinter en polea"],
  cargada:["BB power clean","BB pocket power clean","BB squat clean","High hang power clean","2xkb clean","BB power snatch","BB snatch high pull","KB snatch","KB dead snatch","BB clean and jerk","Complex: pocket clean + front squat + thruster","Grace - 30 BB clean and jerk","Air row","Wall ball shots","Run intervalos","Burpee box jump","KB swing explosivo"],
  accesorio:["Curl bíceps barra W banco scott","Curl bayesian unilateral en polea","Bíceps martillo simultáneo con MC","Curl de bíceps MC inclinado","Curl de bíceps supino codos pared","Bíceps concentrado con MC","Bíceps + press Arnold con MC","Skullcrusher con MC","Tríceps francés con barra W","Tríceps copa con MC","Tríceps en polea con barra recta","Tríceps en polea a un brazo","Scap pull ups","Wall walk","Rotación externa hombros con banda","Facepull en polea con soga","YTWL con carga","Abducción de cadera en máquina","Aducción de cadera en máquina","Patada de glúteo en máquina","Elevación de piernas en paralelas","Espinales tipo superman"]
};

const VARIANTS = {
  1: [
    { id:"v1", name:"V1 · Día único · Cuerpo completo", short:"Full Body",
      days:[
        {label:"Día único",desc:"Cuerpo completo",blocks:[
          {type:"core",badge:"Core",note:"Activación"},
          {type:"bisagra",badge:"Principal A",note:"Más técnico · abre"},
          {type:"sentadilla",badge:"Principal B",note:"Empuje de rodilla"},
          {type:"empuje",badge:"Secundario",note:"Tren superior"},
          {type:"traccion",badge:"Secundario",note:"Tracción"},
          {type:"accesorio",badge:"Accesorio",note:"Cierre"}
        ]}
      ]},
    { id:"v2", name:"V2 · Día único · Posterior + Empuje", short:"Post+Empuje",
      days:[
        {label:"Día único",desc:"Cadena posterior + Empuje",blocks:[
          {type:"core",badge:"Core",note:"Estabilidad lumbar"},
          {type:"bisagra",badge:"Principal",note:"Bisagra · abre"},
          {type:"empuje",badge:"Secundario A",note:"Horizontal"},
          {type:"traccion",badge:"Secundario B",note:"Vertical"},
          {type:"accesorio",badge:"Accesorio",note:"Cierre"}
        ]}
      ]},
    { id:"v3", name:"V3 · Día único · Anterior + Tracción", short:"Ant+Tracción",
      days:[
        {label:"Día único",desc:"Cadena anterior + Tracción",blocks:[
          {type:"core",badge:"Core",note:"Antirotación"},
          {type:"sentadilla",badge:"Principal",note:"Sentadilla · abre"},
          {type:"traccion",badge:"Secundario A",note:"Vertical"},
          {type:"empuje",badge:"Secundario B",note:"Vertical"},
          {type:"accesorio",badge:"Accesorio",note:"Cierre"}
        ]}
      ]},
    { id:"v4", name:"V4 · Día único · Libre", short:"Libre",
      days:[
        {label:"Día único",desc:"Estructura libre",blocks:[
          {type:"core",badge:"Core",note:""},
          {type:"bisagra",badge:"Principal",note:""}
        ]}
      ]}
  ],
  2: [
    { id:"v1", name:"V1 · Bisagra + Empuje / Sentadilla + Tracción", short:"Clásica",
      days:[
        {label:"Día A",desc:"Full Body · Bisagra + Empuje",blocks:[{type:"core",badge:"Core",note:"Antiextensión · prepara bisagra"},{type:"bisagra",badge:"Principal",note:"Bisagra"},{type:"empuje",badge:"Secundario",note:"Empuje"},{type:"accesorio",badge:"Accesorio",note:"Bíceps/Tríceps"}]},
        {label:"Día B",desc:"Full Body · Sentadilla + Tracción",blocks:[{type:"core",badge:"Core",note:"Antirotación · prepara sentadilla"},{type:"sentadilla",badge:"Principal",note:"Sentadilla"},{type:"traccion",badge:"Secundario",note:"Tracción"},{type:"accesorio",badge:"Accesorio",note:"Hombro/Glúteo"}]}
      ]},
    { id:"v2", name:"V2 · Posterior / Anterior", short:"Post/Ant",
      days:[
        {label:"Día A",desc:"Cadena Posterior",blocks:[{type:"core",badge:"Core",note:"Estabilidad lumbar"},{type:"bisagra",badge:"Principal A",note:"Más técnico · abre"},{type:"traccion",badge:"Principal B",note:"Vertical u horizontal"},{type:"accesorio",badge:"Accesorio",note:"Isquio/Bíceps"}]},
        {label:"Día B",desc:"Cadena Anterior",blocks:[{type:"core",badge:"Core",note:"Antiextensión"},{type:"sentadilla",badge:"Principal A",note:"Más técnico · abre"},{type:"empuje",badge:"Principal B",note:"Horizontal o vertical"},{type:"accesorio",badge:"Accesorio",note:"Cuádriceps/Tríceps"}]}
      ]},
    { id:"v3", name:"V3 · Push-Pull dominante", short:"Push/Pull",
      days:[
        {label:"Día A",desc:"Push",blocks:[{type:"core",badge:"Core",note:"Antiextensión"},{type:"bisagra",badge:"Abre",note:"Técnico · Hip thrust o RDL"},{type:"empuje",badge:"Principal",note:"Horiz. + vertical"},{type:"accesorio",badge:"Accesorio",note:"Tríceps/Hombro"}]},
        {label:"Día B",desc:"Pull",blocks:[{type:"core",badge:"Core",note:"Carry/Dinámico"},{type:"sentadilla",badge:"Abre",note:"Técnico · Bilateral"},{type:"traccion",badge:"Principal",note:"Vertical + horizontal"},{type:"accesorio",badge:"Accesorio",note:"Bíceps/Glúteo"}]}
      ]},
    { id:"v4", name:"V4 · Bisagra + Cargada", short:"Potencia",
      days:[
        {label:"Día A",desc:"Potencia + Bisagra",blocks:[{type:"core",badge:"Core",note:"Integración/TGU"},{type:"cargada",badge:"Abre",note:"Clean/Snatch/Push press"},{type:"bisagra",badge:"Principal",note:"Fuerza post-potencia"},{type:"empuje",badge:"Secundario",note:"Vertical · RIR +1"}]},
        {label:"Día B",desc:"Sentadilla + Tracción",blocks:[{type:"core",badge:"Core",note:"Antirotación"},{type:"sentadilla",badge:"Principal",note:"Bilateral o unilateral"},{type:"traccion",badge:"Secundario",note:"Horizontal"},{type:"accesorio",badge:"Accesorio",note:"Bíceps/Glúteo"}]}
      ]}
  ],
  3: [
    { id:"v1", name:"V1 · PPL Clásico · Piernas al final", short:"PPL Clásico",
      days:[
        {label:"Día A",desc:"Empuje",blocks:[{type:"core",badge:"Core",note:"Antiextensión"},{type:"empuje",badge:"Principal",note:"Empuje horizontal"},{type:"empuje",badge:"Secundario",note:"Empuje vertical"},{type:"accesorio",badge:"Accesorio",note:"Tríceps/Hombro"}]},
        {label:"Día B",desc:"Tracción",blocks:[{type:"core",badge:"Core",note:"Antirotación"},{type:"traccion",badge:"Principal",note:"Tracción vertical"},{type:"traccion",badge:"Secundario",note:"Tracción horizontal"},{type:"accesorio",badge:"Accesorio",note:"Bíceps/Manguito"}]},
        {label:"Día C",desc:"Piernas",blocks:[{type:"core",badge:"Core",note:"Estabilidad lumbar"},{type:"bisagra",badge:"Principal · abre",note:"Más técnico del día"},{type:"sentadilla",badge:"Secundario",note:"Unilateral o bilateral"},{type:"accesorio",badge:"Accesorio",note:"Glúteo/Cuádriceps"}]}
      ]},
    { id:"v2", name:"V2 · PPL Invertido · Tracción primero", short:"PPL Invertido",
      days:[
        {label:"Día A",desc:"Tracción",blocks:[{type:"core",badge:"Core",note:"Carry/Dinámico"},{type:"traccion",badge:"Principal",note:"Tracción vertical"},{type:"traccion",badge:"Secundario",note:"Tracción horizontal"},{type:"accesorio",badge:"Accesorio",note:"Bíceps/Rear delt"}]},
        {label:"Día B",desc:"Empuje · vertical abre",blocks:[{type:"core",badge:"Core",note:"Antiextensión"},{type:"empuje",badge:"Principal · abre",note:"Press militar · técnico"},{type:"empuje",badge:"Secundario",note:"Banco/inclinado"},{type:"accesorio",badge:"Accesorio",note:"Tríceps/Hombro"}]},
        {label:"Día C",desc:"Piernas · Sentadilla principal",blocks:[{type:"core",badge:"Core",note:"Antirotación"},{type:"sentadilla",badge:"Principal · abre",note:"Bilateral · énfasis anterior"},{type:"bisagra",badge:"Secundario",note:"RDL/variante ligera"},{type:"accesorio",badge:"Accesorio",note:"Cuádriceps/Glúteo"}]}
      ]},
    { id:"v3", name:"V3 · Upper / Lower / Full", short:"Upper/Lower/Full",
      days:[
        {label:"Día A",desc:"Superior",blocks:[{type:"core",badge:"Core",note:"Antiextensión"},{type:"empuje",badge:"Principal A",note:"Horizontal · abre"},{type:"traccion",badge:"Principal B",note:"Vertical"},{type:"accesorio",badge:"Accesorio",note:"Bíceps/Tríceps"}]},
        {label:"Día B",desc:"Inferior",blocks:[{type:"core",badge:"Core",note:"Estabilidad lumbar"},{type:"bisagra",badge:"Principal A · abre",note:"Más técnico del día"},{type:"sentadilla",badge:"Principal B",note:"Bilateral"},{type:"accesorio",badge:"Accesorio",note:"Glúteo/Cuádriceps"}]},
        {label:"Día C",desc:"Full · cierre",blocks:[{type:"core",badge:"Core",note:"Dinámico/Carry"},{type:"sentadilla",badge:"Repaso A",note:"Unilateral · menor carga"},{type:"traccion",badge:"Repaso B",note:"Horizontal · menor carga"},{type:"accesorio",badge:"Accesorio",note:"Hombro/Glúteo · cierre"}]}
      ]},
    { id:"v4", name:"V4 · Bisagra / Empuje / Sentadilla+Tracción", short:"Bisagra dedicada",
      days:[
        {label:"Día A",desc:"Bisagra dedicada",blocks:[{type:"core",badge:"Core",note:"Estabilidad lumbar"},{type:"bisagra",badge:"Principal · dedicado",note:"Peso muerto + Hip thrust"},{type:"accesorio",badge:"Accesorio",note:"Isquio/Glúteo específico"}]},
        {label:"Día B",desc:"Empuje",blocks:[{type:"core",badge:"Core",note:"Antiextensión"},{type:"empuje",badge:"Principal",note:"Empuje horizontal"},{type:"empuje",badge:"Secundario",note:"Empuje vertical"},{type:"accesorio",badge:"Accesorio",note:"Tríceps/Hombro"}]},
        {label:"Día C",desc:"Sentadilla + Tracción",blocks:[{type:"core",badge:"Core",note:"Antirotación"},{type:"sentadilla",badge:"Principal A · abre",note:"Bilateral o unilateral"},{type:"traccion",badge:"Principal B",note:"Vertical"},{type:"accesorio",badge:"Accesorio",note:"Bíceps/Cuádriceps"}]}
      ]}
  ],
  4: [
    { id:"v1", name:"V1 · ULUL · Upper/Lower alternado", short:"ULUL Clásico",
      days:[
        {label:"Día A",desc:"Upper · Empuje + Tracción",blocks:[{type:"core",badge:"Core",note:"Antiextensión"},{type:"empuje",badge:"Principal · abre",note:"Banco/Floor press"},{type:"traccion",badge:"Secundario",note:"Tracción horizontal"},{type:"accesorio",badge:"Accesorio",note:"Bíceps/Tríceps"}]},
        {label:"Día B",desc:"Lower · Bisagra + Sentadilla",blocks:[{type:"core",badge:"Core",note:"Estabilidad lumbar"},{type:"bisagra",badge:"Principal · abre",note:"Peso muerto/Hip thrust"},{type:"sentadilla",badge:"Secundario",note:"Unilateral"},{type:"accesorio",badge:"Accesorio",note:"Glúteo/Isquio"}]},
        {label:"Día C",desc:"Upper · Tracción + Empuje",blocks:[{type:"core",badge:"Core",note:"Antirotación"},{type:"traccion",badge:"Principal · abre",note:"Dominadas/Dorsalera"},{type:"empuje",badge:"Secundario",note:"Empuje vertical"},{type:"accesorio",badge:"Accesorio",note:"Hombro/Manguito"}]},
        {label:"Día D",desc:"Lower · Sentadilla + Bisagra",blocks:[{type:"core",badge:"Core",note:"Dinámico/Carry"},{type:"sentadilla",badge:"Principal · abre",note:"Bilateral"},{type:"bisagra",badge:"Secundario",note:"RDL/variante"},{type:"accesorio",badge:"Accesorio",note:"Cuádriceps/Glúteo"}]}
      ]},
    { id:"v2", name:"V2 · LULU · Lower primero", short:"LULU Invertido",
      days:[
        {label:"Día A",desc:"Lower · Sentadilla + Bisagra",blocks:[{type:"core",badge:"Core",note:"Antirotación"},{type:"sentadilla",badge:"Principal · abre",note:"Frontal/Trasera"},{type:"bisagra",badge:"Secundario",note:"Hip thrust/RDL"},{type:"accesorio",badge:"Accesorio",note:"Cuádriceps/Glúteo"}]},
        {label:"Día B",desc:"Upper · Empuje vertical abre",blocks:[{type:"core",badge:"Core",note:"Antiextensión"},{type:"empuje",badge:"Principal · abre",note:"Press militar · técnico"},{type:"traccion",badge:"Secundario",note:"Tracción horizontal"},{type:"accesorio",badge:"Accesorio",note:"Tríceps/Bíceps"}]},
        {label:"Día C",desc:"Lower · Bisagra + Sentadilla",blocks:[{type:"core",badge:"Core",note:"Estabilidad lumbar"},{type:"bisagra",badge:"Principal · abre",note:"Peso muerto · técnico"},{type:"sentadilla",badge:"Secundario",note:"Unilateral"},{type:"accesorio",badge:"Accesorio",note:"Isquio/Glúteo"}]},
        {label:"Día D",desc:"Upper · Tracción + Empuje",blocks:[{type:"core",badge:"Core",note:"Antirotación"},{type:"traccion",badge:"Principal · abre",note:"Dominadas"},{type:"empuje",badge:"Secundario",note:"Banco/inclinado"},{type:"accesorio",badge:"Accesorio",note:"Hombro/Manguito"}]}
      ]},
    { id:"v3", name:"V3 · PPL + Full · Cuarto día integrador", short:"PPL + Full",
      days:[
        {label:"Día A",desc:"Empuje",blocks:[{type:"core",badge:"Core",note:"Antiextensión"},{type:"empuje",badge:"Principal",note:"Banco/Floor press"},{type:"empuje",badge:"Secundario",note:"Press militar"},{type:"accesorio",badge:"Accesorio",note:"Tríceps/Hombro"}]},
        {label:"Día B",desc:"Tracción",blocks:[{type:"core",badge:"Core",note:"Carry/Dinámico"},{type:"traccion",badge:"Principal",note:"Dominadas"},{type:"traccion",badge:"Secundario",note:"Remo"},{type:"accesorio",badge:"Accesorio",note:"Bíceps/Rear delt"}]},
        {label:"Día C",desc:"Piernas",blocks:[{type:"core",badge:"Core",note:"Estabilidad lumbar"},{type:"bisagra",badge:"Principal · abre",note:"Peso muerto/Hip thrust"},{type:"sentadilla",badge:"Secundario",note:"Bilateral"},{type:"accesorio",badge:"Accesorio",note:"Cuádriceps/Glúteo"}]},
        {label:"Día D",desc:"Full · cierre",blocks:[{type:"core",badge:"Core",note:"Integración"},{type:"sentadilla",badge:"Repaso A",note:"Unilateral · frec. 2"},{type:"traccion",badge:"Repaso B",note:"Horizontal · frec. 2"},{type:"accesorio",badge:"Accesorio",note:"Hombro/Glúteo · cierre"}]}
      ]},
    { id:"v4", name:"V4 · Patrones dedicados · Bisagra aislada", short:"Patrones dedicados",
      days:[
        {label:"Día A",desc:"Bisagra",blocks:[{type:"core",badge:"Core",note:"Estabilidad lumbar"},{type:"bisagra",badge:"Principal · dedicado",note:"Peso muerto + Hip thrust + RDL"},{type:"accesorio",badge:"Accesorio",note:"Isquio/Glúteo/Gemelos"}]},
        {label:"Día B",desc:"Empuje",blocks:[{type:"core",badge:"Core",note:"Antiextensión"},{type:"empuje",badge:"Principal · dedicado",note:"Banco + Press militar"},{type:"accesorio",badge:"Accesorio",note:"Tríceps/Hombro/Pectoral"}]},
        {label:"Día C",desc:"Sentadilla",blocks:[{type:"core",badge:"Core",note:"Antirotación"},{type:"sentadilla",badge:"Principal · dedicado",note:"Frontal/Trasera + Bulgarian"},{type:"accesorio",badge:"Accesorio",note:"Cuádriceps/Glúteo/Prensa"}]},
        {label:"Día D",desc:"Tracción",blocks:[{type:"core",badge:"Core",note:"Carry/Dinámico"},{type:"traccion",badge:"Principal · dedicado",note:"Dominadas + Remo"},{type:"accesorio",badge:"Accesorio",note:"Bíceps/Rear delt/Manguito"}]}
      ]}
  ],
  5: [
    { id:"v1", name:"V1 · Patrón dedicado + Potencia", short:"Dedicado + Potencia",
      days:[
        {label:"Día A",desc:"Bisagra",blocks:[{type:"core",badge:"Core",note:"Estabilidad lumbar"},{type:"bisagra",badge:"Principal",note:"Peso muerto/Hip thrust"},{type:"accesorio",badge:"Accesorio",note:"Isquio/Glúteo"}]},
        {label:"Día B",desc:"Empuje",blocks:[{type:"core",badge:"Core",note:"Antiextensión"},{type:"empuje",badge:"Principal",note:"Banco + Press militar"},{type:"accesorio",badge:"Accesorio",note:"Tríceps/Hombro"}]},
        {label:"Día C",desc:"Sentadilla",blocks:[{type:"core",badge:"Core",note:"Antirotación"},{type:"sentadilla",badge:"Principal",note:"Bilateral + Unilateral"},{type:"accesorio",badge:"Accesorio",note:"Cuádriceps/Glúteo"}]},
        {label:"Día D",desc:"Tracción",blocks:[{type:"core",badge:"Core",note:"Carry/Dinámico"},{type:"traccion",badge:"Principal",note:"Dominadas + Remo"},{type:"accesorio",badge:"Accesorio",note:"Bíceps/Manguito"}]},
        {label:"Día E",desc:"Cargada/Potencia",blocks:[{type:"core",badge:"Core",note:"Integración/TGU"},{type:"cargada",badge:"Principal · abre",note:"Clean/Snatch/Push press"},{type:"bisagra",badge:"Repaso",note:"Bisagra ligera · RIR 3+"},{type:"accesorio",badge:"Accesorio",note:"Hombro/Cierre"}]}
      ]},
    { id:"v2", name:"V2 · Frecuencia 2 en principales", short:"Alta frecuencia",
      days:[
        {label:"Día A",desc:"Bisagra A · pesado",blocks:[{type:"core",badge:"Core",note:"Estabilidad lumbar"},{type:"bisagra",badge:"Principal · pesado",note:"Peso muerto · RPE máximo"},{type:"accesorio",badge:"Accesorio",note:"Isquio/Glúteo"}]},
        {label:"Día B",desc:"Upper A · Empuje principal",blocks:[{type:"core",badge:"Core",note:"Antiextensión"},{type:"empuje",badge:"Principal · abre",note:"Empuje horizontal"},{type:"traccion",badge:"Secundario",note:"Dominadas"},{type:"accesorio",badge:"Accesorio",note:"Tríceps/Bíceps"}]},
        {label:"Día C",desc:"Sentadilla · dedicada",blocks:[{type:"core",badge:"Core",note:"Antirotación"},{type:"sentadilla",badge:"Principal · dedicado",note:"Bilateral + Unilateral"},{type:"accesorio",badge:"Accesorio",note:"Cuádriceps/Glúteo"}]},
        {label:"Día D",desc:"Upper B · Tracción principal",blocks:[{type:"core",badge:"Core",note:"Carry/Dinámico"},{type:"traccion",badge:"Principal · abre",note:"Tracción vertical + horiz."},{type:"empuje",badge:"Secundario",note:"Press militar"},{type:"accesorio",badge:"Accesorio",note:"Hombro/Rear delt"}]},
        {label:"Día E",desc:"Bisagra B · liviano",blocks:[{type:"core",badge:"Core",note:"Estabilidad lumbar"},{type:"bisagra",badge:"Principal · liviano",note:"Hip thrust · frec. 2"},{type:"accesorio",badge:"Accesorio",note:"Glúteo/Isquio específico"}]}
      ]},
    { id:"v3", name:"V3 · Upper/Lower × 2 + Potencia", short:"UL×2 + Potencia",
      days:[
        {label:"Día A",desc:"Upper A · Empuje",blocks:[{type:"core",badge:"Core",note:"Antiextensión"},{type:"empuje",badge:"Principal · abre",note:"Horizontal + vertical"},{type:"traccion",badge:"Secundario",note:"Tracción horizontal"},{type:"accesorio",badge:"Accesorio",note:"Tríceps/Bíceps"}]},
        {label:"Día B",desc:"Lower A · Bisagra",blocks:[{type:"core",badge:"Core",note:"Estabilidad lumbar"},{type:"bisagra",badge:"Principal · abre",note:"Peso muerto · técnico"},{type:"sentadilla",badge:"Secundario",note:"Unilateral"},{type:"accesorio",badge:"Accesorio",note:"Glúteo/Isquio"}]},
        {label:"Día C",desc:"Potencia · separador",blocks:[{type:"core",badge:"Core",note:"Integración/TGU"},{type:"cargada",badge:"Principal · abre",note:"Clean/Snatch · base técnica"},{type:"accesorio",badge:"Accesorio",note:"Hombro/Core específico"}]},
        {label:"Día D",desc:"Upper B · Tracción",blocks:[{type:"core",badge:"Core",note:"Antirotación"},{type:"traccion",badge:"Principal · abre",note:"Vertical + horizontal"},{type:"empuje",badge:"Secundario",note:"Press militar"},{type:"accesorio",badge:"Accesorio",note:"Hombro/Manguito"}]},
        {label:"Día E",desc:"Lower B · Sentadilla",blocks:[{type:"core",badge:"Core",note:"Dinámico/Carry"},{type:"sentadilla",badge:"Principal · abre",note:"Bilateral · énfasis anterior"},{type:"bisagra",badge:"Secundario",note:"Hip thrust/RDL · frec. 2"},{type:"accesorio",badge:"Accesorio",note:"Cuádriceps/Glúteo"}]}
      ]},
    { id:"v4", name:"V4 · Especialización Bisagra + Full cierre", short:"Bisagra especializada",
      days:[
        {label:"Día A",desc:"Bisagra · pesado",blocks:[{type:"core",badge:"Core",note:"Estabilidad lumbar"},{type:"bisagra",badge:"Principal · pesado",note:"Peso muerto · RPE máximo"},{type:"accesorio",badge:"Accesorio",note:"Isquio/Glúteo específico"}]},
        {label:"Día B",desc:"Empuje",blocks:[{type:"core",badge:"Core",note:"Antiextensión"},{type:"empuje",badge:"Principal",note:"Horizontal + vertical"},{type:"accesorio",badge:"Accesorio",note:"Tríceps/Hombro"}]},
        {label:"Día C",desc:"Posterior + Anterior",blocks:[{type:"core",badge:"Core",note:"Estabilidad lumbar"},{type:"bisagra",badge:"Principal A · abre",note:"Hip thrust · frec. 2"},{type:"sentadilla",badge:"Principal B",note:"Bilateral"},{type:"accesorio",badge:"Accesorio",note:"Cuádriceps/Glúteo"}]},
        {label:"Día D",desc:"Tracción",blocks:[{type:"core",badge:"Core",note:"Carry/Dinámico"},{type:"traccion",badge:"Principal",note:"Vertical + horizontal"},{type:"accesorio",badge:"Accesorio",note:"Bíceps/Rear delt"}]},
        {label:"Día E",desc:"Full · cierre",blocks:[{type:"core",badge:"Core",note:"Integración"},{type:"sentadilla",badge:"Repaso A",note:"Unilateral · frec. 2"},{type:"traccion",badge:"Repaso B",note:"Horizontal · frec. 2"},{type:"accesorio",badge:"Accesorio",note:"Hombro/Glúteo/Cierre"}]}
      ]}
  ]
};

// Legacy - used as fallback
const DAY_TEMPLATES={
  1:VARIANTS[1][0].days, 2:VARIANTS[2][0].days, 3:VARIANTS[3][0].days,
  4:VARIANTS[4][0].days, 5:VARIANTS[5][0].days
}

let currentRole=null,currentAthlete=null,athletes=[],planDays=[],customEx={};

function loginCoach(){
  currentRole="coach";
  document.getElementById("login-screen").style.display="none";
  document.getElementById("topbar").style.display="flex";
  document.getElementById("role-label").textContent="Entrenador";
  document.getElementById("coach-app").style.display="block";
  loadAthletes();
}

async function loginAthlete(){
  const token=document.getElementById("athlete-token-input").value.trim();
  if(!token){alert("Ingresá tu código");return;}
  try{
    const data=await sb("atletas?token=eq."+token+"&select=*");
    if(!data||!data.length){alert("Código incorrecto");return;}
    currentRole="athlete";currentAthlete=data[0];
    document.getElementById("login-screen").style.display="none";
    document.getElementById("topbar").style.display="flex";
    document.getElementById("role-label").textContent=currentAthlete.nombre;
    document.getElementById("athlete-app").style.display="block";
    loadAthleteView();
  }catch(e){alert("Error al conectar");console.error(e);}
}

window.addEventListener("load",()=>{
  const t=new URLSearchParams(window.location.search).get("t");
  if(t){document.getElementById("athlete-token-input").value=t;loginAthlete();}
});

function logout(){
  currentRole=null;currentAthlete=null;
  document.getElementById("login-screen").style.display="flex";
  document.getElementById("topbar").style.display="none";
  document.getElementById("coach-app").style.display="none";
  document.getElementById("athlete-app").style.display="none";
  window.history.replaceState({},"",window.location.pathname);
}

async function loadAthletes(){
  try{
    athletes=await sb("atletas?select=*,planes(id,fase,microciclo,activo,created_at)&order=created_at.desc");
    renderAthletes();populateAthleteSelect();
  }catch(e){console.error(e);}
}

function renderAthletes(){
  const el=document.getElementById("athletes-list");
  if(!athletes.length){el.innerHTML='<div class="empty">No hay atletas todavía.</div>';return;}
  el.innerHTML=athletes.map(a=>{
    const ap=a.planes?.find(p=>p.activo);const ph=ap?.fase||"—";const pc=PHASE_COLORS[ph]||"var(--dim)";
    return `<div class="athlete-card" onclick="viewAthlete('${a.id}')">
      <div class="athlete-name">${a.nombre}</div>
      <div class="athlete-meta">${a.dias_por_semana} días/sem${a.email?" · "+a.email:""}</div>
      ${a.activo===false?'<span class="athlete-badge" style="color:var(--dim);border-color:rgba(240,236,227,0.15)">📦 Archivado</span>':ap?`<span class="athlete-badge" style="color:${pc};border-color:${pc}40;background:${pc}15">${ph} · ${PHASE_LABELS[ph]}</span>`:'<span class="athlete-badge" style="color:var(--dim);border-color:rgba(240,236,227,0.15)">Sin plan activo</span>'}
      <div style="margin-top:10px;display:flex;gap:5px;flex-wrap:wrap;border-top:1px solid rgba(240,236,227,0.06);padding-top:10px;">
        <button class="btn btn-ghost btn-sm" onclick="event.stopPropagation();showShareLink('${a.token}','${a.nombre}')" style="display:inline-flex">🔗 Link</button>
        <button class="btn btn-ghost btn-sm" onclick="event.stopPropagation();setupNewPlan('${a.id}')" style="display:inline-flex">+ Plan</button>
        <button class="btn btn-ghost btn-sm" onclick="event.stopPropagation();openEditAthleteModal('${a.id}')" style="display:inline-flex">✏️ Editar</button>
        <button class="btn btn-ghost btn-sm" onclick="event.stopPropagation();archiveAthlete('${a.id}','${a.nombre}',${a.activo!==false})" style="display:inline-flex;color:var(--dim)">${a.activo===false?"↩ Reactivar":"📦 Archivar"}</button>
        <button class="btn btn-ghost btn-sm" onclick="event.stopPropagation();deleteAthlete('${a.id}','${a.nombre}')" style="display:inline-flex;color:#d47070">✕ Borrar</button>
      </div>
    </div>`;
  }).join("");
}

function populateAthleteSelect(){
  const sel=document.getElementById("np-atleta");if(!sel)return;
  sel.innerHTML=athletes.map(a=>`<option value="${a.id}">${a.nombre} (${a.dias_por_semana} día${a.dias_por_semana===1?'':'s'})</option>`).join("");
}

async function viewAthlete(id){
  const a=athletes.find(x=>x.id===id);if(!a)return;
  document.getElementById("detail-title").innerHTML=`<em>${a.nombre}</em>`;
  const planes=await sb("planes?atleta_id=eq."+id+"&order=created_at.desc");
  const regs=await sb("registros?atleta_id=eq."+id+"&order=fecha.desc&limit=20");
  document.getElementById("atleta-detail-content").innerHTML=`
    <div class="ath-bar">
      <div class="ath-item"><div class="ath-lbl">Email</div><div class="ath-val">${a.email||"—"}</div></div>
      <div class="ath-item"><div class="ath-lbl">Frecuencia</div><div class="ath-val">${a.dias_por_semana} días/sem</div></div>
      <div class="ath-item"><div class="ath-lbl">Planes</div><div class="ath-val">${planes.length}</div></div>
      <div class="ath-item"><div class="ath-lbl">Registros</div><div class="ath-val">${regs.length}</div></div>
    </div>

    <div style="display:flex;gap:8px;margin-bottom:14px;flex-wrap:wrap;padding:14px;background:rgba(240,236,227,0.04);border-radius:3px;border:1px solid rgba(240,236,227,0.08);">
      <button class="btn btn-primary" onclick="setupNewPlan('${a.id}')" style="display:inline-flex">+ Nuevo plan</button>
      <button class="btn btn-secondary" onclick="showShareLink('${a.token}','${a.nombre}')" style="display:inline-flex">🔗 Link atleta</button>
      <button class="btn btn-secondary" onclick="openEditAthleteModal('${a.id}')" style="display:inline-flex">✏️ Editar</button>
      <button class="btn btn-secondary" onclick="archiveAthlete('${a.id}','${a.nombre}',${a.activo!==false})" style="display:inline-flex">${a.activo===false?"↩ Reactivar":"📦 Archivar"}</button>
      <button class="btn btn-danger" onclick="deleteAthlete('${a.id}','${a.nombre}')" style="display:inline-flex;background:rgba(138,74,74,0.2);color:#d47070;border-color:rgba(138,74,74,0.3)">✕ Eliminar</button>
    </div>

    ${a.notas?`<div class="card" style="margin-bottom:10px"><div class="card-lbl">Notas</div><div style="font-size:12px;color:var(--dim);line-height:1.6">${a.notas}</div></div>`:""}

    <div class="card">
      <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:12px;">
        <div class="card-lbl" style="margin-bottom:0">Planes</div>
      </div>
      ${!planes.length?'<div class="empty" style="padding:16px 0">Sin planes todavía. Creá el primero con el botón de arriba.</div>':planes.map(p=>`
        <div style="padding:10px 0;border-bottom:1px solid rgba(240,236,227,0.05);">
          <div style="display:flex;align-items:center;gap:10px;flex-wrap:wrap;">
            <span style="font-size:12px;font-weight:700;color:${PHASE_COLORS[p.fase]||"var(--gold)"}">${p.fase} · ${PHASE_LABELS[p.fase]||""}</span>
            <span style="font-size:11px;color:var(--dim)">Micro ${p.microciclo} · Sem ${p.semana} · ${new Date(p.created_at).toLocaleDateString("es-AR")}</span>
            ${p.activo?'<span style="font-size:9px;color:var(--success);font-weight:700;letter-spacing:1px">ACTIVO</span>':""}
            <div style="margin-left:auto;display:flex;gap:6px;flex-shrink:0;">
              ${!p.activo?`<button class="btn btn-ghost btn-sm" onclick="activatePlan('${p.id}','${a.id}')" style="display:inline-flex">✓ Activar</button>`:""}
              <button class="btn btn-ghost btn-sm" onclick="deletePlan('${p.id}','${a.id}')" style="display:inline-flex;color:#d47070">✕ Borrar</button>
            </div>
          </div>
          <div id="plan-detail-${p.id}" style="display:none;margin-top:10px;"></div>
          <button class="btn btn-ghost btn-sm" style="margin-top:6px;font-size:9px;" onclick="togglePlanDetail('${p.id}')">Ver ejercicios ↓</button>
        </div>`).join("")}
    </div>

    ${regs.length?`<div class="card" style="margin-top:10px">
      <div class="card-lbl">Últimos registros</div>
      ${regs.slice(0,8).map(r=>`<div style="padding:7px 0;border-bottom:1px solid rgba(240,236,227,0.05)">
        <div style="display:flex;gap:10px;flex-wrap:wrap">
          <span style="font-size:11px;color:var(--dim)">${new Date(r.fecha).toLocaleDateString("es-AR")}</span>
          ${r.peso_utilizado?`<span style="font-size:12px;color:var(--gold);font-weight:600">${r.peso_utilizado}</span>`:""}
          ${r.estado_energia?`<span style="font-size:10px;color:var(--dim)">Estado: ${r.estado_energia}/10</span>`:""}
        </div>
        ${r.comentario_atleta?`<div style="font-size:11px;color:var(--dim);margin-top:2px;font-style:italic">"${r.comentario_atleta}"</div>`:""}
      </div>`).join("")}
    </div>`:""}
  `;
  coachTab("atleta-detail");
}

async function togglePlanDetail(planId){
  const el=document.getElementById("plan-detail-"+planId);
  if(!el) return;
  if(el.style.display!=="none"){el.style.display="none";return;}
  el.style.display="block";
  if(el.innerHTML) return; // already loaded
  el.innerHTML='<div style="font-size:11px;color:var(--dim)">Cargando...</div>';
  try{
    const dias=await sb("plan_dias?plan_id=eq."+planId+"&order=orden");
    if(!dias.length){el.innerHTML='<div style="font-size:11px;color:var(--dim)">Sin días cargados.</div>';return;}
    let html="";
    for(const dia of dias){
      const bloques=await sb("plan_bloques?dia_id=eq."+dia.id+"&order=orden");
      html+=`<div style="margin-bottom:8px"><div style="font-size:11px;font-weight:700;color:var(--gold);letter-spacing:1px;margin-bottom:4px">${dia.label} — ${dia.descripcion||""}</div>`;
      for(const b of bloques){
        const ejs=await sb("plan_ejercicios?bloque_id=eq."+b.id+"&order=orden");
        const c=PC[b.tipo]||"#607080";
        html+=`<div style="margin-left:10px;margin-bottom:4px">
          <span style="font-size:9px;font-weight:700;letter-spacing:1px;color:${c};text-transform:uppercase">${b.badge}</span>
          ${ejs.map(e=>`<div style="font-size:12px;color:var(--white);padding:2px 0">${e.nombre} <span style="color:var(--dim);font-size:10px">${e.series}×${e.reps} · ${e.rir||e.rpe||""}</span></div>`).join("")}
        </div>`;
      }
      html+="</div>";
    }
    el.innerHTML=html;
  }catch(e){el.innerHTML='<div style="font-size:11px;color:var(--danger)">Error al cargar.</div>';console.error(e);}
}

async function activatePlan(planId, atletaId){
  try{
    // Deactivate all plans for this athlete
    await sb("planes?atleta_id=eq."+atletaId,"PATCH",{activo:false});
    // Activate selected
    await sb("planes?id=eq."+planId,"PATCH",{activo:true});
    viewAthlete(atletaId);
  }catch(e){alert("Error: "+e.message);}
}

async function deletePlan(planId, atletaId){
  if(!confirm("¿Borrar este plan? Se eliminarán también todos sus días, bloques y ejercicios.")) return;
  try{
    await sb("planes?id=eq."+planId,"DELETE");
    viewAthlete(atletaId);
  }catch(e){alert("Error: "+e.message);}
}

function openNewAthleteModal(){document.getElementById("modal-new-athlete").classList.add("open");}

async function saveNewAthlete(){
  const nombre=document.getElementById("na-nombre").value.trim();
  if(!nombre){alert("El nombre es obligatorio");return;}
  try{
    await sb("atletas","POST",{nombre,email:document.getElementById("na-email").value.trim()||null,dias_por_semana:parseInt(document.getElementById("na-dias").value),notas:document.getElementById("na-notas").value.trim()||null});
    closeModal("modal-new-athlete");
    ["na-nombre","na-email","na-notas"].forEach(id=>document.getElementById(id).value="");
    await loadAthletes();
  }catch(e){alert("Error: "+e.message);}
}

function getInt(){
  const ph=document.getElementById("np-fase")?.value||"F1";
  const mc=parseInt(document.getElementById("np-micro")?.value||1);
  const wk=document.getElementById("np-semana")?.value||"A";
  return INT[ph]?.[mc]?.[wk]||INT.F1[1].A;
}

function updateIntPreview(){
  const i=getInt();const el=document.getElementById("np-int-preview");if(!el)return;
  el.innerHTML=`
    <span class="ipill" style="color:#4a7fa5;border-color:#4a7fa530;background:rgba(74,127,165,0.1)">📊 ${i.s} series</span>
    <span class="ipill" style="color:#5b9e8a;border-color:#5b9e8a30;background:rgba(91,158,138,0.1)">🔢 ${i.r} reps</span>
    <span class="ipill" style="color:#c9a84c;border-color:#c9a84c30;background:rgba(201,168,76,0.1)">⚡ ${i.rpe}</span>
    <span class="ipill" style="color:#a57060;border-color:#a5706030;background:rgba(165,112,96,0.1)">🎯 ${i.rir}</span>
    ${i.note?`<span class="ipill" style="color:var(--dim);border-color:rgba(240,236,227,0.1)">📝 ${i.note}</span>`:""}
  `;
  if(planDays.length) renderDays();
}

function onAthleteChange(){
  const id=document.getElementById("np-atleta")?.value;
  if(!id) return;
  setTimeout(()=>{updateIntPreview();renderVariantSelector();},50);
}

function setupNewPlan(athleteId){
  // Switch tab
  document.querySelectorAll(".view").forEach(v=>v.classList.remove("active"));
  document.querySelectorAll(".tab-btn").forEach(t=>t.classList.remove("active"));
  document.getElementById("view-nuevo-plan").classList.add("active");
  document.querySelectorAll(".tab-btn")[1]?.classList.add("active");
  populateAthleteSelect();
  if(athleteId){const s=document.getElementById("np-atleta");if(s)s.value=athleteId;}
  setTimeout(()=>{
    updateIntPreview();
    renderVariantSelector();
  },80);
}

function renderVariantSelector(){
  const id=document.getElementById("np-atleta")?.value;
  const a=athletes.find(x=>x.id===id);
  const days=parseInt(a?.dias_por_semana)||4;
  const variants=VARIANTS[days]||VARIANTS[4];
  const el=document.getElementById("variant-options");
  if(!el) return;

  // Debug
  console.log("Athlete days:", days, "Variants available:", variants?.length, "VARIANTS keys:", Object.keys(VARIANTS));

  // Show header with frequency info
  const freqLabel = days===1 ? "1 día / semana" : days+" días / semana";
  el.innerHTML=`<div style="font-size:10px;color:var(--dim);letter-spacing:1px;margin-bottom:8px;padding-bottom:8px;border-bottom:1px solid rgba(240,236,227,0.06)">
    Mostrando variantes para <span style="color:var(--gold);font-weight:600">${freqLabel}</span>
    ${!variants||!variants.length?'<span style="color:#d47070"> — Sin variantes definidas para esta frecuencia</span>':''}
  </div>`+variants.map((v,i)=>`
    <label style="display:flex;align-items:flex-start;gap:10px;padding:10px 12px;border-radius:3px;border:1px solid rgba(240,236,227,0.1);cursor:pointer;transition:all .15s;background:var(--faint)"
      onmouseover="this.style.borderColor='rgba(201,168,76,0.3)'"
      onmouseout="this.style.borderColor=document.getElementById('var-${v.id}').checked?'rgba(201,168,76,0.5)':'rgba(240,236,227,0.1)'"
    >
      <input type="radio" name="variant" id="var-${v.id}" value="${i}" ${i===0?"checked":""} style="margin-top:3px;accent-color:var(--gold)" onchange="applyVariant(${i})">
      <div>
        <div style="font-size:13px;font-weight:600;color:var(--white);margin-bottom:2px">${v.name}</div>
        <div style="font-size:10px;color:var(--dim);letter-spacing:1px">${v.days.length} días · ${v.days.map(d=>d.desc).join(" / ")}</div>
      </div>
    </label>
  `).join("")+`
    <label style="display:flex;align-items:flex-start;gap:10px;padding:10px 12px;border-radius:3px;border:1px solid rgba(240,236,227,0.1);cursor:pointer;transition:all .15s;background:var(--faint)">
      <input type="radio" name="variant" id="var-custom" value="custom" style="margin-top:3px;accent-color:var(--gold)" onchange="applyVariant('custom')">
      <div>
        <div style="font-size:13px;font-weight:600;color:var(--gold-lt);margin-bottom:2px">Personalizada — armo yo la estructura</div>
        <div style="font-size:10px;color:var(--dim);letter-spacing:1px">Días vacíos · agregás patrones y bloques libremente</div>
      </div>
    </label>
  `;

  // Apply first variant by default
  applyVariant(0);
}

function applyVariant(idx){
  const id=document.getElementById("np-atleta")?.value;
  const a=athletes.find(x=>x.id===id);
  const days=parseInt(a?.dias_por_semana)||4;

  const customCtrl=document.getElementById("custom-day-controls");

  if(idx==="custom"){
    planDays=[];
    if(customCtrl) customCtrl.style.display="block";
    document.getElementById("np-days").innerHTML=`<div class="empty" style="padding:20px;border:1px dashed rgba(240,236,227,0.15);border-radius:3px">Definí la cantidad de días arriba y hacé click en "Generar días vacíos"</div>`;
    return;
  }

  if(customCtrl) customCtrl.style.display="none";

  const variants=VARIANTS[days]||VARIANTS[4];
  const variant=variants[idx];
  if(!variant) return;

  planDays=variant.days.map(d=>({
    label:d.label, desc:d.desc,
    blocks:d.blocks.map(b=>({
      type:b.type, badge:b.badge, note:b.note,
      exercises:[{name:"",custom:"",videoUrl:"",overrideInt:false,series:"",reps:""}]
    }))
  }));

  setTimeout(()=>renderDays(), 50);
}

function initCustomDays(){
  const n=parseInt(document.getElementById("custom-days-count")?.value)||4;
  planDays=[];
  for(let i=0;i<n;i++){
    planDays.push({
      label:"Día "+(i+1),
      desc:"Personalizado",
      blocks:[{type:"core",badge:"Core",note:"",exercises:[{name:"",custom:"",videoUrl:"",overrideInt:false,series:"",reps:""}]}]
    });
  }
  renderDays();
}

function renderDays(){
  const container=document.getElementById("np-days");if(!container)return;
  const int=getInt();container.innerHTML="";
  planDays.forEach((day,di)=>{
    const dc=document.createElement("div");dc.className="day-card";
    dc.innerHTML=`<div class="day-header"><div class="day-num">${di+1}</div><div><div class="day-name">${day.label}</div><div class="day-desc">${day.desc}</div></div></div><div id="di-${di}"></div>
      <div class="add-block-row">
        <button class="btn btn-ghost btn-sm" onclick="addBlock(${di})">＋ Agregar bloque</button>
      </div>
      <div id="abp-${di}" style="display:none;margin:0 14px 12px;background:var(--navy-lt);border:1px solid rgba(201,168,76,0.25);border-radius:3px;padding:12px;">
        <div style="font-size:10px;letter-spacing:2px;color:var(--gold);text-transform:uppercase;margin-bottom:10px">Configurar nuevo bloque</div>
        <div style="display:grid;grid-template-columns:1fr 1fr 1fr;gap:8px;margin-bottom:8px;">
          <div class="fg">
            <label class="fl">Patrón</label>
            <select class="fs" id="abt-${di}">
              <option value="core">Core</option>
              <option value="bisagra">Bisagra</option>
              <option value="sentadilla">Sentadilla</option>
              <option value="empuje">Empuje</option>
              <option value="traccion">Tracción</option>
              <option value="cargada">Cargada</option>
              <option value="accesorio">Accesorio</option>
            </select>
          </div>
          <div class="fg">
            <label class="fl">Rol en el día</label>
            <select class="fs" id="abb-${di}">
              <option value="Principal">Principal</option>
              <option value="Secundario">Secundario</option>
              <option value="Core">Core</option>
              <option value="Accesorio">Accesorio</option>
              <option value="Repaso">Repaso</option>
              <option value="Principal A">Principal A</option>
              <option value="Principal B">Principal B</option>
              <option value="Abre">Abre</option>
              <option value="Extra">Extra</option>
            </select>
          </div>
          <div class="fg">
            <label class="fl">Nota (opcional)</label>
            <input class="fi" type="text" id="abn-${di}" placeholder="ej: énfasis glúteo">
          </div>
        </div>
        <div style="display:flex;gap:6px;">
          <button class="btn btn-primary btn-sm" onclick="confirmAddBlock(${di})">Agregar</button>
          <button class="btn btn-ghost btn-sm" onclick="addBlock(${di})">Cancelar</button>
        </div>
      </div>`;
    container.appendChild(dc);renderDayBlocks(di,int);
  });
}

function renderDayBlocks(di,int){
  int=int||getInt();const container=document.getElementById("di-"+di);if(!container)return;
  container.innerHTML="";
  planDays[di].blocks.forEach((block,bi)=>{
    const c=PC[block.type]||"#607080";
    const isMain=block.badge==="Principal"||block.badge==="Core";
    const bi2=isMain?int:{...int,r:!isNaN(parseInt(int.r))?String(Math.max(1,parseInt(int.r)-1)):int.r,rir:int.rir.replace(/\d+/,n=>Math.min(4,parseInt(n)+1))};
    const el=document.createElement("div");el.className="block open";el.id="b-"+di+"-"+bi;el.style.borderLeftColor=c;
    const exRows=block.exercises.map((ex,ei)=>`
      <div style="margin-bottom:7px;${ei>0?'padding-top:6px;border-top:1px dashed rgba(240,236,227,0.07)':''}">
        ${block.exercises.length>1?`<div style="font-size:8px;letter-spacing:1px;color:${c};text-transform:uppercase;margin-bottom:3px">${String.fromCharCode(65+ei)}.</div>`:''}
        <div class="ex-row">
          <div class="ex-mini-group"><div class="ex-mini-lbl">Biblioteca</div>
            <select class="ex-sel" style="border-left-color:${c}60" onchange="uef(${di},${bi},${ei},'name',this.value)">
              <option value="">— Elegir —</option>
              ${(EX[block.type]||[]).concat(customEx[block.type]||[]).map(e=>`<option value="${e}" ${e===ex.name?'selected':''}>${e}</option>`).join('')}
            </select>
          </div>
          <div class="ex-mini-group"><div class="ex-mini-lbl">O escribir</div>
            <input class="ex-inp" type="text" value="${ex.custom||''}" placeholder="Nombre libre..." oninput="uef(${di},${bi},${ei},'custom',this.value)">
          </div>
          <button class="btn btn-ghost btn-sm" style="padding-top:14px" onclick="rmEx(${di},${bi},${ei})">✕</button>
        </div>
        <div style="display:flex;gap:5px;margin-top:3px;flex-wrap:wrap;align-items:flex-end;">
          <div class="ex-mini-group" style="flex:1;min-width:90px"><div class="ex-mini-lbl">Video URL</div><input class="ex-mini" type="text" value="${ex.videoUrl||''}" placeholder="youtube.com/..." oninput="uef(${di},${bi},${ei},'videoUrl',this.value)"></div>
          <div class="ex-mini-group" style="flex:0 0 55px"><div class="ex-mini-lbl">Series</div><input class="ex-mini" type="text" value="${ex.overrideInt&&ex.series?ex.series:bi2.s}" style="text-align:center" oninput="uef(${di},${bi},${ei},'series',this.value)"></div>
          <div class="ex-mini-group" style="flex:0 0 55px"><div class="ex-mini-lbl">Reps</div><input class="ex-mini" type="text" value="${ex.overrideInt&&ex.reps?ex.reps:bi2.r}" style="text-align:center" oninput="uef(${di},${bi},${ei},'reps',this.value)"></div>
          <label style="display:flex;align-items:center;gap:3px;font-size:9px;color:var(--dim);cursor:pointer;padding-bottom:6px"><input type="checkbox" ${ex.overrideInt?'checked':''} onchange="tov(${di},${bi},${ei},this.checked)">Int. propia</label>
        </div>
      </div>`).join('');
    el.innerHTML=`
      <div class="block-header" onclick="this.closest('.block').classList.toggle('open')">
        <span class="block-badge" style="color:${c};border-color:${c}40;background:${c}15">${block.badge}</span>
        <span class="block-type-lbl">${block.type}</span>
        <span style="font-size:9px;color:var(--dim)">${bi2.s}×${bi2.r} · ${bi2.rir}</span>
        <span class="block-chevron">↓</span>
      </div>
      <div class="block-body">
        <div>${exRows}</div>
        <div class="block-actions">
          <button class="btn btn-ghost btn-sm" onclick="addExToBlock(${di},${bi})">＋ Ejercicio</button>
          ${block.exercises.length>1?`<button class="btn btn-ghost btn-sm" onclick="rmLastEx(${di},${bi})">− Quitar último</button>`:''}
          ${bi>0?`<button class="btn btn-ghost btn-sm" style="color:var(--danger);margin-left:auto" onclick="rmBlock(${di},${bi})">✕ Quitar bloque</button>`:''}
        </div>
      </div>`;
    container.appendChild(el);
  });
}

function uef(di,bi,ei,f,v){
  if(!planDays[di]?.blocks[bi]?.exercises[ei])return;
  planDays[di].blocks[bi].exercises[ei][f]=v;
  if(f==="custom"&&v.trim()){const t=planDays[di].blocks[bi].type;if(!customEx[t])customEx[t]=[];if(!customEx[t].includes(v.trim())&&!EX[t]?.includes(v.trim()))customEx[t].push(v.trim());}
}
function tov(di,bi,ei,c){planDays[di].blocks[bi].exercises[ei].overrideInt=c;renderDayBlocks(di);}
function addExToBlock(di,bi){planDays[di].blocks[bi].exercises.push({name:"",custom:"",videoUrl:"",overrideInt:false,series:"",reps:""});renderDayBlocks(di);}
function rmEx(di,bi,ei){if(planDays[di].blocks[bi].exercises.length>1){planDays[di].blocks[bi].exercises.splice(ei,1);renderDayBlocks(di);}}
function rmLastEx(di,bi){if(planDays[di].blocks[bi].exercises.length>1){planDays[di].blocks[bi].exercises.pop();renderDayBlocks(di);}}
function rmBlock(di,bi){planDays[di].blocks.splice(bi,1);renderDayBlocks(di);}
function addBlock(di){
  const picker=document.getElementById("abp-"+di);
  if(picker) picker.style.display=picker.style.display==="none"?"block":"none";
}
function confirmAddBlock(di){
  const type=document.getElementById("abt-"+di)?.value||"accesorio";
  const badge=document.getElementById("abb-"+di)?.value||"Bloque";
  const note=document.getElementById("abn-"+di)?.value||"";
  planDays[di].blocks.push({type,badge,note,exercises:[{name:"",custom:"",videoUrl:"",overrideInt:false,series:"",reps:""}]});
  const p=document.getElementById("abp-"+di);if(p)p.style.display="none";
  renderDayBlocks(di);
}

async function savePlan(){
  const aid=document.getElementById("np-atleta")?.value;if(!aid){alert("Seleccioná un atleta");return;}
  const int=getInt();
  try{
    const planes=await sb("planes","POST",{atleta_id:aid,fase:document.getElementById("np-fase").value,microciclo:parseInt(document.getElementById("np-micro").value),semana:document.getElementById("np-semana").value,activo:true});
    const planId=planes[0].id;
    for(let di=0;di<planDays.length;di++){
      const day=planDays[di];
      const dias=await sb("plan_dias","POST",{plan_id:planId,orden:di+1,label:day.label,descripcion:day.desc});
      const diaId=dias[0].id;
      for(let bi=0;bi<day.blocks.length;bi++){
        const block=day.blocks[bi];
        const bloques=await sb("plan_bloques","POST",{dia_id:diaId,orden:bi+1,tipo:block.type,badge:block.badge,nota:block.note});
        const bloqueId=bloques[0].id;
        const isMain=block.badge==="Principal"||block.badge==="Core";
        const bi2=isMain?int:{...int,r:!isNaN(parseInt(int.r))?String(Math.max(1,parseInt(int.r)-1)):int.r};
        for(let ei=0;ei<block.exercises.length;ei++){
          const ex=block.exercises[ei];
          const nombre=ex.custom?.trim()||ex.name||"";if(!nombre)continue;
          await sb("plan_ejercicios","POST",{bloque_id:bloqueId,orden:ei+1,nombre,series:ex.overrideInt&&ex.series?parseInt(ex.series):bi2.s,reps:ex.overrideInt&&ex.reps?ex.reps:bi2.r,rpe:bi2.rpe,rir:bi2.rir,video_url:ex.videoUrl||null});
        }
      }
    }
    alert("✓ Plan guardado");await loadAthletes();coachTab("atletas");
  }catch(e){alert("Error: "+e.message);console.error(e);}
}

async function loadFeedback(){
  try{
    // Get registros with comments only (athlete left a comment)
    const registros=await sb("registros?comentario_atleta=not.is.null&select=*,plan_ejercicios(nombre,bloque_id,plan_bloques(badge,tipo,plan_dias(label,orden,planes(atleta_id,fase,atletas(nombre))))),comentarios_entrenador(id,texto,created_at)&order=created_at.desc&limit=100");

    const sin=registros.filter(r=>!r.comentarios_entrenador||!r.comentarios_entrenador.length);
    if(sin.length){
      document.getElementById("feedback-dot").style.display="inline-block";
      document.getElementById("notif-count").textContent=sin.length+" sin responder";
      document.getElementById("notif-count").style.display="inline";
    } else {
      document.getElementById("feedback-dot").style.display="none";
      document.getElementById("notif-count").style.display="none";
    }

    const el=document.getElementById("feedback-list");
    if(!registros.length){
      el.innerHTML='<div class="empty">No hay comentarios de atletas todavía.</div>';return;
    }

    // Group by athlete
    const byAthlete={};
    registros.forEach(r=>{
      const name=r.plan_ejercicios?.plan_bloques?.plan_dias?.planes?.atletas?.nombre||"Atleta";
      const aid=r.atleta_id;
      const key=aid;
      if(!byAthlete[key]) byAthlete[key]={name, registros:[]};
      byAthlete[key].registros.push(r);
    });

    el.innerHTML=Object.entries(byAthlete).map(([aid,ath])=>{
      const sinResp=ath.registros.filter(r=>!r.comentarios_entrenador?.length);
      return `<div style="margin-bottom:16px">
        <div style="display:flex;align-items:center;gap:10px;margin-bottom:8px;padding-bottom:8px;border-bottom:1px solid rgba(201,168,76,0.2)">
          <div style="font-size:16px;font-weight:600;font-family:'Cormorant Garamond',serif;font-style:italic">${ath.name}</div>
          ${sinResp.length?`<span style="font-size:9px;font-weight:700;letter-spacing:1px;color:#d47070;background:rgba(138,74,74,0.15);border:1px solid rgba(138,74,74,0.3);padding:2px 7px;border-radius:2px">${sinResp.length} SIN RESPONDER</span>`:""}
        </div>
        ${ath.registros.map(r=>{
          const ex=r.plan_ejercicios;
          const dl=ex?.plan_bloques?.plan_dias?.label||"";
          const exNombre=ex?.nombre||"—";
          const fase=ex?.plan_bloques?.plan_dias?.planes?.fase||"";
          const yr=r.comentarios_entrenador?.length>0;
          const resp=r.comentarios_entrenador?.[0];
          return `<div class="feedback-panel" style="margin-left:8px;border-left:3px solid ${yr?"var(--success)":"rgba(201,168,76,0.4)"}">
            <div style="display:flex;justify-content:space-between;flex-wrap:wrap;gap:4px;margin-bottom:6px">
              <div style="font-size:12px;color:var(--dim)">${dl}${fase?" · "+fase:""} · Sem ${r.semana_tipo} · ${new Date(r.fecha).toLocaleDateString("es-AR")}</div>
              <div style="font-size:9px;color:${yr?"var(--success)":"#d47070"};font-weight:700;letter-spacing:1px">${yr?"✓ RESPONDIDO":"● PENDIENTE"}</div>
            </div>
            <div style="font-size:13px;font-weight:600;color:var(--white);margin-bottom:4px">${exNombre}</div>
            <div style="font-size:11px;color:var(--dim);margin-bottom:8px">
              ${r.peso_utilizado?`<span style="color:var(--gold);font-weight:600">${r.peso_utilizado}</span> · `:""}
              ${r.reps_realizadas?r.reps_realizadas+" · ":""}
              ${r.rpe_percibido?"RPE "+r.rpe_percibido+" · ":""}
              ${r.estado_energia?"Estado "+r.estado_energia+"/10":""}
            </div>
            <div style="background:rgba(240,236,227,0.05);border-left:2px solid rgba(201,168,76,0.3);padding:8px 10px;border-radius:0 3px 3px 0;margin-bottom:8px;font-size:12px;color:var(--white);font-style:italic">
              "${r.comentario_atleta}"
            </div>
            ${yr?`<div style="background:rgba(74,138,90,0.1);border-left:2px solid var(--success);padding:8px 10px;border-radius:0 3px 3px 0;font-size:11px;color:var(--dim)">
              <span style="color:var(--success);font-size:9px;letter-spacing:1px;font-weight:700">TU RESPUESTA · </span>${resp?.texto||""}
            </div>`:`<div class="fp-reply-area">
              <input class="fi" type="text" id="rp-${r.id}" placeholder="Escribí tu respuesta..." style="flex:1">
              <button class="btn btn-primary btn-sm" onclick="sendFeedback('${r.id}','${r.atleta_id}','${r.ejercicio_id}')">Enviar</button>
            </div>`}
          </div>`;
        }).join("")}
      </div>`;
    }).join("");
  }catch(e){console.error(e);}
}

async function sendFeedback(rid,aid,eid){
  const t=document.getElementById("rp-"+rid)?.value.trim();if(!t)return;
  try{await sb("comentarios_entrenador","POST",{registro_id:rid,atleta_id:aid,ejercicio_id:eid,texto:t});loadFeedback();}
  catch(e){alert("Error: "+e.message);}
}

async function loadAthleteView(){
  const el=document.getElementById("athlete-content");
  try{
    const planes=await sb("planes?atleta_id=eq."+currentAthlete.id+"&order=created_at.desc");
    const plan=planes.find(p=>p.activo)||planes[0];
    if(!plan){
      el.innerHTML=`<div style="padding:60px 20px;text-align:center">
        <div style="font-family:'Cormorant Garamond',serif;font-size:26px;margin-bottom:8px">Hola, <em style="color:var(--gold-lt)">${currentAthlete.nombre}</em></div>
        <div style="font-size:13px;color:var(--dim)">Tu entrenador está preparando tu plan. Volvé pronto.</div>
      </div>`;
      return;
    }

    // Determine which week to show
    const diasPlan=await sb("plan_dias?plan_id=eq."+plan.id+"&order=orden");
    if(!diasPlan.length){
      el.innerHTML=`<div style="padding:60px 20px;text-align:center">
        <div style="font-family:'Cormorant Garamond',serif;font-size:26px;margin-bottom:8px">Hola, <em style="color:var(--gold-lt)">${currentAthlete.nombre}</em></div>
        <div style="font-size:13px;color:var(--dim)">Tu entrenador está configurando tu plan. Volvé en unos minutos.</div>
      </div>`;
      return;
    }

    // Check completed days for each week
    const compA=await sb("dias_completados?atleta_id=eq."+currentAthlete.id+"&semana_tipo=eq.A&select=dia_id");
    const compB=await sb("dias_completados?atleta_id=eq."+currentAthlete.id+"&semana_tipo=eq.B&select=dia_id");
    const compAIds=compA.map(x=>x.dia_id);
    const compBIds=compB.map(x=>x.dia_id);
    const allADone=diasPlan.every(d=>compAIds.includes(d.id));
    const allBDone=diasPlan.every(d=>compBIds.includes(d.id));

    // Decide active week
    let activeWeek="A";
    if(allADone) activeWeek="B";

    const phaseColors={F1:"#4a7fa5",F2:"#5b9e8a",F3:"#c9a84c",F4:"#a57060"};
    const phaseLabels={F1:"Ordenar",F2:"Construir",F3:"Intensificar",F4:"Consolidar"};

    let html=`<div style="margin-bottom:16px">
      <div style="font-family:'Cormorant Garamond',serif;font-size:26px;font-weight:300;margin-bottom:10px">
        Hola, <em style="color:var(--gold-lt)">${currentAthlete.nombre}</em>
      </div>
      <div style="display:flex;gap:6px;margin-bottom:14px;flex-wrap:wrap;">
        <button onclick="setAthleteWeek('A')" id="tab-week-A"
          style="padding:7px 14px;border-radius:3px;border:1px solid;font-family:'Barlow Condensed',sans-serif;font-size:10px;font-weight:700;letter-spacing:2px;text-transform:uppercase;cursor:pointer;transition:all .2s;
          background:${activeWeek==='A'?'var(--gold)':'transparent'};color:${activeWeek==='A'?'var(--navy)':'var(--dim)'};border-color:${activeWeek==='A'?'var(--gold)':'rgba(240,236,227,0.2)'}">
          Semana A ${allADone?'✓':''}
        </button>
        <button onclick="setAthleteWeek('B')" id="tab-week-B"
          style="padding:7px 14px;border-radius:3px;border:1px solid;font-family:'Barlow Condensed',sans-serif;font-size:10px;font-weight:700;letter-spacing:2px;text-transform:uppercase;cursor:pointer;transition:all .2s;
          ${allADone?'background:'+(activeWeek==='B'?'var(--gold)':'transparent')+';color:'+(activeWeek==='B'?'var(--navy)':'var(--dim)')+';border-color:'+(activeWeek==='B'?'var(--gold)':'rgba(240,236,227,0.2)'):'opacity:0.3;cursor:not-allowed;background:transparent;color:var(--dim);border-color:rgba(240,236,227,0.1)'}">
          Semana B ${allBDone?'✓':'🔒'}
        </button>
        <button onclick="showAthleteHistory()" id="tab-history"
          style="padding:7px 14px;border-radius:3px;border:1px solid rgba(240,236,227,0.2);font-family:'Barlow Condensed',sans-serif;font-size:10px;font-weight:700;letter-spacing:2px;text-transform:uppercase;cursor:pointer;background:transparent;color:var(--dim)">
          📋 Historial
        </button>
      </div>
      <div id="athlete-week-content"></div>
      <div id="athlete-history-content" style="display:none"></div>
    </div>`;

    el.innerHTML=html;

    // Store plan data globally for week switching
    window._athletePlan={plan, diasPlan, compAIds, compBIds, allADone};
    renderAthleteWeek(activeWeek);

  }catch(e){
    el.innerHTML=`<div style="padding:40px;text-align:center;color:var(--dim)">Error al cargar. <button onclick="loadAthleteView()" class="btn btn-secondary btn-sm" style="margin-left:8px">Reintentar</button></div>`;
    console.error(e);
  }
}

function setAthleteWeek(week){
  const p=window._athletePlan;
  if(!p) return;
  if(week==='B'&&!p.allADone) return; // locked
  renderAthleteWeek(week);
  // Update tab styles
  ['A','B'].forEach(w=>{
    const btn=document.getElementById("tab-week-"+w);
    if(!btn) return;
    const isActive=w===week;
    const locked=w==='B'&&!p.allADone;
    btn.style.background=isActive?'var(--gold)':'transparent';
    btn.style.color=isActive?'var(--navy)':locked?'var(--dim)':'var(--dim)';
    btn.style.borderColor=isActive?'var(--gold)':'rgba(240,236,227,0.2)';
  });
}

async function renderAthleteWeek(week){
  const p=window._athletePlan;
  if(!p) return;
  const {plan, diasPlan, compAIds, compBIds}=p;
  const container=document.getElementById("athlete-week-content");
  if(!container) return;

  const compIds=week==='A'?compAIds:compBIds;
  container.innerHTML='<div style="color:var(--dim);font-size:12px;padding:20px 0">Cargando...</div>';

  let html="";
  for(const dia of diasPlan){
    const isDone=compIds.includes(dia.id);
    const bloques=await sb("plan_bloques?dia_id=eq."+dia.id+"&order=orden");

    html+=`<div class="day-card" style="margin-bottom:10px;${isDone?'opacity:0.75':''}">
      <div class="day-header" style="justify-content:space-between">
        <div style="display:flex;align-items:center;gap:10px">
          <div class="day-num" style="${isDone?'background:var(--success)':'background:var(--gold)'}">${isDone?'✓':dia.orden}</div>
          <div><div class="day-name">${dia.label}</div><div class="day-desc">${dia.descripcion||""}</div></div>
        </div>
      </div>`;

    for(const bloque of bloques){
      const ejercicios=await sb("plan_ejercicios?bloque_id=eq."+bloque.id+"&order=orden");
      const c=PC[bloque.tipo]||"#607080";
      html+=`<div class="block open" style="border-left-color:${c}">
        <div class="block-header" onclick="this.closest('.block').classList.toggle('open')">
          <span class="block-badge" style="color:${c};border-color:${c}40;background:${c}15">${bloque.badge}</span>
          <span class="block-type-lbl">${bloque.tipo}${bloque.nota?" · "+bloque.nota:""}</span>
          <span class="block-chevron">↓</span>
        </div>
        <div class="block-body">`;

      for(const ej of ejercicios){
        const regs=await sb("registros?ejercicio_id=eq."+ej.id+"&atleta_id=eq."+currentAthlete.id+"&semana_tipo=eq."+week+"&order=created_at.desc&limit=1");
        const reg=regs[0]||null;
        const comments=reg?await sb("comentarios_entrenador?registro_id=eq."+reg.id+"&order=created_at.asc"):[];
        const hasUnread=comments.length===0&&reg?.comentario_atleta;

        html+=`<div class="registro-card" style="${hasUnread?'border-color:rgba(201,168,76,0.3)':''}">
          <div class="reg-header" onclick="this.nextElementSibling.classList.toggle('open')">
            <div style="flex:1">
              <div class="reg-ex-name">${ej.nombre}${hasUnread?'<span style="display:inline-block;width:7px;height:7px;border-radius:50%;background:var(--gold);margin-left:6px;vertical-align:middle"></span>':''}</div>
              <div style="font-size:10px;color:var(--dim);margin-top:2px">
                ${ej.series}×${ej.reps}${ej.rpe?" · "+ej.rpe:""}${ej.rir?" · "+ej.rir:""}
                ${ej.video_url?` · <a href="${ej.video_url}" target="_blank" style="color:var(--gold);text-decoration:none">▶ Video</a>`:""}
              </div>
            </div>
            <span style="font-size:16px;color:${reg?"var(--success)":"var(--dim)"}">${reg?"✓":"○"}</span>
          </div>
          <div class="reg-body ${reg?"open":""}">
            <div class="reg-grid">
              <div class="fg"><label class="fl">Peso utilizado</label>
                <input class="fi" type="text" id="w-${ej.id}-${week}" value="${reg?.peso_utilizado||""}" placeholder="ej: 80kg"></div>
              <div class="fg"><label class="fl">Reps realizadas</label>
                <input class="fi" type="text" id="r-${ej.id}-${week}" value="${reg?.reps_realizadas||""}" placeholder="ej: 8/8/7"></div>
              <div class="fg"><label class="fl">RPE percibido</label>
                <input class="fi" type="text" id="p-${ej.id}-${week}" value="${reg?.rpe_percibido||""}" placeholder="ej: 8.5"></div>
              <div class="fg"><label class="fl">Estado (1-10)</label>
                <input class="fi" type="number" min="1" max="10" id="e-${ej.id}-${week}" value="${reg?.estado_energia||""}"></div>
            </div>
            <div class="fg" style="margin-bottom:8px">
              <label class="fl">Comentarios / sensaciones</label>
              <textarea class="ftextarea" id="c-${ej.id}-${week}" placeholder="¿Cómo se sintió? ¿Qué limitó? ¿Alguna molestia?">${reg?.comentario_atleta||""}</textarea>
            </div>
            ${comments.length>0?`<div style="margin-bottom:8px">
              ${comments.map(cm=>`<div class="feedback-box" style="margin-bottom:5px">
                <div class="feedback-label">💬 Tu entrenador</div>
                <div class="feedback-text">${cm.texto}</div>
              </div>`).join("")}
            </div>`:""}
            <div style="display:flex;align-items:center;gap:8px;">
              <button class="btn btn-primary btn-sm" onclick="saveReg('${ej.id}','${week}','${reg?.id||""}')">Guardar</button>
              <span class="saved-indicator" id="si-${ej.id}-${week}">✓ Guardado</span>
            </div>
          </div>
        </div>`;
      }
      html+=`</div></div>`;
    }

    // Day completion checkbox
    html+=`<div style="padding:12px 16px;border-top:1px solid rgba(240,236,227,0.06);display:flex;align-items:center;gap:10px;">
      <label style="display:flex;align-items:center;gap:8px;cursor:pointer;user-select:none;${isDone?'opacity:0.6':''}">
        <input type="checkbox" ${isDone?"checked":""} ${isDone?"disabled":""}
          onchange="markDayDone('${dia.id}','${week}',this.checked,'${plan.id}')"
          style="width:16px;height:16px;accent-color:var(--gold);cursor:pointer">
        <span style="font-size:11px;font-weight:700;letter-spacing:1px;text-transform:uppercase;color:${isDone?'var(--success)':'var(--dim)'}">
          ${isDone?"✓ Entrenamiento completado":"Marcar como completado"}
        </span>
      </label>
    </div>
    </div>`;
  }

  // Show next week message if both done
  if(week==='B'&&p.allADone){
    const compBIds2=await sb("dias_completados?atleta_id=eq."+currentAthlete.id+"&semana_tipo=eq.B&select=dia_id");
    const allBDone=diasPlan.every(d=>compBIds2.map(x=>x.dia_id).includes(d.id));
    if(allBDone){
      html+=`<div style="text-align:center;padding:24px;background:rgba(201,168,76,0.06);border:1px solid rgba(201,168,76,0.2);border-radius:4px;margin-top:8px">
        <div style="font-size:18px;margin-bottom:6px">🎯</div>
        <div style="font-size:14px;font-weight:600;color:var(--gold-lt);margin-bottom:4px">¡Microciclo completado!</div>
        <div style="font-size:12px;color:var(--dim)">Tu próximo microciclo estará disponible pronto.</div>
      </div>`;
    }
  }

  container.innerHTML=html;
}

async function markDayDone(diaId, week, checked, planId){
  try{
    if(checked){
      await sb("dias_completados","POST",{dia_id:diaId,atleta_id:currentAthlete.id,semana_tipo:week});
    } else {
      await sb("dias_completados?dia_id=eq."+diaId+"&atleta_id=eq."+currentAthlete.id+"&semana_tipo=eq."+week,"DELETE");
    }
    // Reload to check if all days done
    await loadAthleteView();
  }catch(e){
    // If duplicate, ignore
    if(!e.message.includes("duplicate")) console.error(e);
    await loadAthleteView();
  }
}

async function showAthleteHistory(){
  const histEl=document.getElementById("athlete-history-content");
  const weekEl=document.getElementById("athlete-week-content");
  if(!histEl||!weekEl) return;

  // Toggle
  if(histEl.style.display!=="none"){
    histEl.style.display="none";weekEl.style.display="block";return;
  }
  weekEl.style.display="none";
  histEl.style.display="block";
  histEl.innerHTML='<div style="color:var(--dim);font-size:12px;padding:20px 0">Cargando historial...</div>';

  try{
    const regs=await sb("registros?atleta_id=eq."+currentAthlete.id+"&order=fecha.desc,created_at.desc&select=*,plan_ejercicios(nombre,plan_bloques(badge,tipo,plan_dias(label,planes(fase,microciclo,semana))))");

    if(!regs.length){
      histEl.innerHTML='<div style="padding:30px;text-align:center;color:var(--dim)">Todavía no hay entrenamientos registrados.</div>';
      return;
    }

    // Group by date
    const byDate={};
    regs.forEach(r=>{
      const key=r.fecha;
      if(!byDate[key]) byDate[key]=[];
      byDate[key].push(r);
    });

    let html=`<div style="margin-bottom:12px;font-size:11px;color:var(--dim);letter-spacing:1px;text-transform:uppercase">${regs.length} registros · ${Object.keys(byDate).length} sesiones</div>`;

    Object.entries(byDate).forEach(([fecha,rs])=>{
      const ex=rs[0];
      const fase=ex?.plan_ejercicios?.plan_bloques?.plan_dias?.planes?.fase||"";
      const micro=ex?.plan_ejercicios?.plan_bloques?.plan_dias?.planes?.microciclo||"";
      const sem=ex?.plan_ejercicios?.plan_bloques?.plan_dias?.planes?.semana||"";
      const dia=ex?.plan_ejercicios?.plan_bloques?.plan_dias?.label||"";

      html+=`<div class="card" style="margin-bottom:8px">
        <div style="display:flex;justify-content:space-between;align-items:baseline;margin-bottom:10px;flex-wrap:wrap;gap:6px">
          <div style="font-size:13px;font-weight:600">${new Date(fecha+"T12:00:00").toLocaleDateString("es-AR",{weekday:"long",day:"numeric",month:"long"})}</div>
          <div style="font-size:10px;color:var(--gold);letter-spacing:1px">${fase?fase+" · Micro "+micro+" · Sem "+sem:""} ${dia}</div>
        </div>
        <div style="overflow-x:auto">
        <table style="width:100%;border-collapse:collapse;font-size:11px">
          <thead>
            <tr style="border-bottom:1px solid rgba(240,236,227,0.1)">
              <th style="text-align:left;padding:5px 8px;font-size:9px;letter-spacing:1px;color:var(--gold);text-transform:uppercase;white-space:nowrap">Ejercicio</th>
              <th style="text-align:center;padding:5px 8px;font-size:9px;letter-spacing:1px;color:var(--gold);text-transform:uppercase;white-space:nowrap">Peso</th>
              <th style="text-align:center;padding:5px 8px;font-size:9px;letter-spacing:1px;color:var(--gold);text-transform:uppercase;white-space:nowrap">Reps</th>
              <th style="text-align:center;padding:5px 8px;font-size:9px;letter-spacing:1px;color:var(--gold);text-transform:uppercase;white-space:nowrap">RPE</th>
              <th style="text-align:center;padding:5px 8px;font-size:9px;letter-spacing:1px;color:var(--gold);text-transform:uppercase;white-space:nowrap">Estado</th>
            </tr>
          </thead>
          <tbody>
            ${rs.map(r=>`<tr style="border-bottom:1px solid rgba(240,236,227,0.05)">
              <td style="padding:6px 8px;color:var(--white);font-weight:500">${r.plan_ejercicios?.nombre||"—"}</td>
              <td style="padding:6px 8px;text-align:center;color:var(--gold-lt);font-weight:600">${r.peso_utilizado||"—"}</td>
              <td style="padding:6px 8px;text-align:center;color:var(--dim)">${r.reps_realizadas||"—"}</td>
              <td style="padding:6px 8px;text-align:center;color:var(--dim)">${r.rpe_percibido||"—"}</td>
              <td style="padding:6px 8px;text-align:center;color:var(--dim)">${r.estado_energia?r.estado_energia+"/10":"—"}</td>
            </tr>
            ${r.comentario_atleta?`<tr><td colspan="5" style="padding:4px 8px 8px;font-size:10px;color:var(--dim);font-style:italic;border-bottom:1px solid rgba(240,236,227,0.05)">"${r.comentario_atleta}"</td></tr>`:""}
            `).join("")}
          </tbody>
        </table>
        </div>
      </div>`;
    });

    histEl.innerHTML=html;
  }catch(e){
    histEl.innerHTML='<div style="color:var(--danger);padding:20px">Error al cargar historial.</div>';
    console.error(e);
  }
}
async function saveReg(ejId,sem,existId){
  const key=ejId+"-"+sem;
  const data={ejercicio_id:ejId,atleta_id:currentAthlete.id,semana_tipo:sem,
    peso_utilizado:document.getElementById("w-"+key)?.value.trim()||null,
    reps_realizadas:document.getElementById("r-"+key)?.value.trim()||null,
    rpe_percibido:document.getElementById("p-"+key)?.value.trim()||null,
    estado_energia:document.getElementById("e-"+key)?.value?parseInt(document.getElementById("e-"+key).value):null,
    comentario_atleta:document.getElementById("c-"+key)?.value.trim()||null,
    fecha:new Date().toISOString().split("T")[0]
  };
  try{
    if(existId) await sb("registros?id=eq."+existId,"PATCH",data);
    else await sb("registros","POST",data);
    const ind=document.getElementById("si-"+key);
    if(ind){ind.classList.add("show");setTimeout(()=>ind.classList.remove("show"),2000);}
  }catch(e){alert("Error al guardar: "+e.message);console.error(e);}
}

function showShareLink(token,nombre){
  const link=window.location.origin+window.location.pathname+"?t="+token;
  document.getElementById("share-link-text").textContent=link;
  document.getElementById("modal-share").classList.add("open");
}

function copyShareLink(){
  navigator.clipboard.writeText(document.getElementById("share-link-text").textContent).then(()=>{
    const b=event.target;b.textContent="✓ Copiado!";setTimeout(()=>b.textContent="📋 Copiar",2000);
  });
}

function coachTab(tab){
  document.querySelectorAll(".view").forEach(v=>v.classList.remove("active"));
  document.querySelectorAll(".tab-btn").forEach(t=>t.classList.remove("active"));
  const vm={atletas:"view-atletas","nuevo-plan":"view-nuevo-plan",feedback:"view-feedback","atleta-detail":"view-atleta-detail"};
  const tm={atletas:0,"nuevo-plan":1,feedback:2};
  document.getElementById(vm[tab])?.classList.add("active");
  if(tm[tab]!==undefined)document.querySelectorAll(".tab-btn")[tm[tab]]?.classList.add("active");
  if(tab==="nuevo-plan"){
    populateAthleteSelect();
    setTimeout(()=>{updateIntPreview();renderVariantSelector();},50);
  }
  if(tab==="feedback")loadFeedback();
}

async function deleteAthlete(id, nombre){
  if(!confirm("¿Eliminar a "+nombre+"? Se borrarán todos sus planes, ejercicios y registros. Esta acción no se puede deshacer.")) return;
  try{
    // 1. Get all plans
    const planes=await sb("planes?atleta_id=eq."+id+"&select=id");
    for(const plan of planes){
      // 2. Get all dias
      const dias=await sb("plan_dias?plan_id=eq."+plan.id+"&select=id");
      for(const dia of dias){
        // 3. Get all bloques
        const bloques=await sb("plan_bloques?dia_id=eq."+dia.id+"&select=id");
        for(const bloque of bloques){
          // 4. Delete ejercicios → registros → comentarios handled by cascade
          await sb("plan_ejercicios?bloque_id=eq."+bloque.id,"DELETE");
        }
        await sb("plan_bloques?dia_id=eq."+dia.id,"DELETE");
      }
      await sb("plan_dias?plan_id=eq."+plan.id,"DELETE");
    }
    // 5. Delete registros directos del atleta
    await sb("registros?atleta_id=eq."+id,"DELETE");
    await sb("comentarios_entrenador?atleta_id=eq."+id,"DELETE");
    // 6. Delete planes
    await sb("planes?atleta_id=eq."+id,"DELETE");
    // 7. Finally delete athlete
    await sb("atletas?id=eq."+id,"DELETE");
    await loadAthletes();
    coachTab("atletas");
    alert("✓ Atleta eliminado correctamente");
  }catch(e){
    alert("Error al eliminar: "+e.message);
    console.error(e);
  }
}

async function archiveAthlete(id, nombre, currentState){
  const action = currentState ? "archivar" : "reactivar";
  if(!confirm("¿"+action.charAt(0).toUpperCase()+action.slice(1)+" a "+nombre+"?")) return;
  try{
    await sb("atletas?id=eq."+id,"PATCH",{activo: !currentState});
    await loadAthletes();
  }catch(e){alert("Error: "+e.message);}
}

function openEditAthleteModal(id){
  const a=athletes.find(x=>x.id===id);
  if(!a) return;
  document.getElementById("ea-id").value=a.id;
  document.getElementById("ea-nombre").value=a.nombre||"";
  document.getElementById("ea-email").value=a.email||"";
  document.getElementById("ea-dias").value=a.dias_por_semana||4;
  document.getElementById("ea-notas").value=a.notas||"";
  document.getElementById("modal-edit-athlete").classList.add("open");
}

async function saveEditAthlete(){
  const id=document.getElementById("ea-id").value;
  const nombre=document.getElementById("ea-nombre").value.trim();
  if(!nombre){alert("El nombre es obligatorio");return;}
  try{
    await sb("atletas?id=eq."+id,"PATCH",{
      nombre,
      email:document.getElementById("ea-email").value.trim()||null,
      dias_por_semana:parseInt(document.getElementById("ea-dias").value),
      notas:document.getElementById("ea-notas").value.trim()||null,
    });
    closeModal("modal-edit-athlete");
    await loadAthletes();
  }catch(e){alert("Error: "+e.message);}
}

function closeModal(id){document.getElementById(id).classList.remove("open");}
document.querySelectorAll(".modal-overlay").forEach(m=>m.addEventListener("click",e=>{if(e.target===m)m.classList.remove("open");}));

if("serviceWorker" in navigator){window.addEventListener("load",()=>navigator.serviceWorker.register("/sw.js").catch(()=>{}));}
</script>
</body>
</html>
