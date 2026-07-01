<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Auditor FOGAPE — Maxxa</title>
<script src="https://cdnjs.cloudflare.com/ajax/libs/pdf.js/3.11.174/pdf.min.js"></script>
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{font-family:-apple-system,BlinkMacSystemFont,'Segoe UI',sans-serif;background:#f5f5f3;color:#1a1a18;font-size:14px}
.header{background:#1E2235;color:#fff;padding:14px 24px;display:flex;align-items:center;gap:12px}
.logo{width:34px;height:34px;background:#F47920;border-radius:8px;display:flex;align-items:center;justify-content:center;font-weight:700;font-size:15px;color:#fff;flex-shrink:0}
.ht{font-size:15px;font-weight:500}.hs{font-size:11px;color:rgba(255,255,255,.55);margin-top:1px}
.layout{display:grid;grid-template-columns:340px 1fr;min-height:calc(100vh - 58px)}
.left{background:#fff;border-right:1px solid #e5e4df;padding:18px;display:flex;flex-direction:column;gap:14px;overflow-y:auto;max-height:calc(100vh - 58px)}
.right{padding:20px 24px;overflow-y:auto;max-height:calc(100vh - 58px);display:flex;flex-direction:column;gap:14px}
.st{font-size:11px;font-weight:500;color:#888780;text-transform:uppercase;letter-spacing:.06em;margin-bottom:8px}
.akbox{background:#f0f4ff;border:1px solid #b5d4f4;border-radius:9px;padding:12px 14px}
.akbox label{font-size:12px;color:#0c447c;font-weight:500;display:block;margin-bottom:5px}
.aki{width:100%;border:1px solid #b5d4f4;border-radius:6px;padding:7px 9px;font-size:12px;font-family:monospace;color:#1a1a18;background:#fff}
.aki:focus{outline:none;border-color:#378add}
.akh{font-size:10px;color:#378add;margin-top:4px}
.field{display:flex;flex-direction:column;gap:3px;margin-bottom:8px}
.field label{font-size:12px;color:#5f5e5a;font-weight:500}
.field input,.field select{border:1px solid #d3d1c7;border-radius:6px;padding:7px 9px;font-size:12px;font-family:inherit;color:#1a1a18;background:#fff;width:100%}
.field input:focus{outline:none;border-color:#F47920}
.drop-area{border:2px dashed #d3d1c7;border-radius:12px;padding:20px;text-align:center;background:#fafaf8;transition:all .2s;cursor:pointer;position:relative}
.drop-area:hover,.drop-area.drag{border-color:#F47920;background:#fff8f3}
.drop-area input{position:absolute;inset:0;opacity:0;cursor:pointer;width:100%;height:100%}
.drop-icon{font-size:28px;margin-bottom:8px}
.drop-label{font-size:13px;font-weight:500;color:#3d3d3a}
.drop-hint{font-size:11px;color:#888780;margin-top:4px}
.file-list{display:flex;flex-direction:column;gap:6px;margin-top:10px}
.file-item{display:flex;align-items:center;gap:8px;padding:7px 10px;background:#f5f5f3;border-radius:7px;font-size:12px}
.file-item .fi-name{flex:1;color:#3d3d3a;font-weight:500;overflow:hidden;text-overflow:ellipsis;white-space:nowrap}
.file-item .fi-size{color:#888780;font-size:11px;flex-shrink:0}
.file-item .fi-del{cursor:pointer;color:#888780;font-size:14px;flex-shrink:0;background:none;border:none;padding:0}
.file-item .fi-del:hover{color:#e24b4a}
.file-icon{font-size:16px;flex-shrink:0}
.btn{background:#F47920;color:#fff;border:none;border-radius:8px;padding:12px 16px;font-size:13px;font-weight:500;cursor:pointer;width:100%;display:flex;align-items:center;justify-content:center;gap:7px;font-family:inherit;transition:background .15s}
.btn:hover{background:#d9660f}
.btn:disabled{background:#d3d1c7;cursor:not-allowed;color:#888780}
.spin{width:14px;height:14px;border:2px solid rgba(255,255,255,.4);border-top-color:#fff;border-radius:50%;animation:spin .7s linear infinite;flex-shrink:0}
@keyframes spin{to{transform:rotate(360deg)}}
.log{background:#1E2235;border-radius:8px;padding:12px;font-family:monospace;font-size:11px;color:#9faccc;line-height:1.75;max-height:160px;overflow-y:auto;display:none}
.lok{color:#5DCAA5}.lerr{color:#F09595}.lwarn{color:#FAC775}.linfo{color:#85B7EB}
.empty{flex:1;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:10px;color:#888780;text-align:center;padding:40px 24px}
.ei{font-size:48px;opacity:.3}
.eh2{font-size:15px;font-weight:500;color:#5f5e5a}
.ep{font-size:12px;line-height:1.6;max-width:300px}
.grid2{display:grid;grid-template-columns:1fr 1fr;gap:7px;margin-top:12px;font-size:11px;color:#888780}
.mc{background:#fff;border:1px solid #e5e4df;border-radius:7px;padding:8px 10px}
.mc strong{display:block;font-size:12px;color:#3d3d3a;margin-bottom:2px}
.rhead{background:#fff;border-radius:10px;border:1px solid #e5e4df;padding:16px 18px}
.vb{display:inline-block;padding:5px 14px;border-radius:16px;font-size:13px;font-weight:500}
.vA{background:#eaf3de;color:#27500a}
.vR{background:#fcebeb;color:#791f1f}
.vP{background:#faeeda;color:#633806}
.rmeta{display:grid;grid-template-columns:repeat(3,1fr);gap:8px;margin-top:12px}
.rmi{background:#f5f5f3;border-radius:7px;padding:8px 10px}
.rml{font-size:10px;color:#888780;font-weight:500;text-transform:uppercase;letter-spacing:.04em}
.rmv{font-size:12px;color:#1a1a18;font-weight:500;margin-top:2px;word-break:break-word}
.srow{display:flex;align-items:center;gap:10px;margin-top:12px}
.sbar{flex:1;height:7px;background:#e5e4df;border-radius:4px;overflow:hidden}
.sfill{height:100%;border-radius:4px}
.rb{background:#fff;border-radius:10px;border:1px solid #e5e4df;overflow:hidden;margin-bottom:2px}
.rbh{padding:11px 14px;background:#f5f5f3;border-bottom:1px solid #e5e4df;display:flex;align-items:center;gap:8px;cursor:pointer;user-select:none}
.rbht{font-size:13px;font-weight:500;flex:1}
.pills{display:flex;gap:5px;margin-left:auto}
.pill{display:inline-flex;align-items:center;font-size:10px;padding:2px 7px;border-radius:9px}
.pok{background:#eaf3de;color:#27500a}.perr{background:#fcebeb;color:#791f1f}.pwarn{background:#faeeda;color:#633806}
.chev{font-size:10px;color:#888780;transition:transform .2s}
.chev.open{transform:rotate(180deg)}
.rbb{display:none}.rbb.open{display:block}
table.at{width:100%;border-collapse:collapse;font-size:12px}
table.at th{padding:7px 12px;text-align:left;font-size:10px;font-weight:500;color:#888780;text-transform:uppercase;letter-spacing:.04em;border-bottom:1px solid #e5e4df;background:#fafaf8}
table.at td{padding:9px 12px;border-bottom:1px solid #f1efe8;vertical-align:top;line-height:1.5;color:#3d3d3a}
table.at tr:last-child td{border-bottom:none}
table.at tr:hover td{background:#fafaf8}
.est{display:inline-block;padding:2px 8px;border-radius:4px;font-size:10px;font-weight:500;white-space:nowrap}
.eC{background:#eaf3de;color:#27500a}.eE{background:#fcebeb;color:#791f1f}.eA{background:#faeeda;color:#633806}.eP{background:#f1efe8;color:#5f5e5a}
.ob{background:#fff;border-radius:10px;border:1px solid #e5e4df;padding:16px 18px}
.oi{padding:10px 12px;border-radius:7px;border-left:3px solid;margin-bottom:8px;font-size:12px;line-height:1.55}
.oi:last-child{margin-bottom:0}
.oE{background:#fcebeb;border-color:#e24b4a;color:#501313}
.oA{background:#faeeda;border-color:#ef9f27;color:#412402}
.oI{background:#e6f1fb;border-color:#378add;color:#042c53}
.ol{font-weight:500;font-size:11px;margin-bottom:3px}
.ar{display:flex;gap:8px;justify-content:flex-end}
.bsm{border:1px solid #d3d1c7;border-radius:7px;padding:7px 13px;font-size:12px;cursor:pointer;color:#3d3d3a;background:transparent;font-family:inherit}
.bsm:hover{border-color:#888780;background:#f5f5f3}
.pw{height:4px;background:#e5e4df;border-radius:2px;margin-top:8px}
.pb{height:4px;background:#F47920;border-radius:2px;transition:width .4s;width:0%}
.file-count{font-size:12px;color:#5f5e5a;margin-top:6px;text-align:center}
@media print{.left,.header,.ar,.log,.pw{display:none!important}.layout{display:block}.rbb{display:block!important}.right{max-height:none;overflow:visible;padding:0}}
</style>
</head>
<body>
<div class="header">
  <div class="logo">M</div>
  <div>
    <div class="ht">Auditor FOGAPE — Cobranza Judicial</div>
    <div class="hs">44 puntos de control · Maxxa · GPT-4o Vision</div>
  </div>
</div>
<div class="layout">
<div class="left">

  <div class="akbox">
    <label>🔑 API Key de OpenAI</label>
    <input class="aki" type="password" id="ak" placeholder="sk-proj-..." autocomplete="off"/>
    <div class="akh">Tu key no se guarda ni se comparte. Solo llama a OpenAI desde tu navegador.</div>
  </div>

  <div>
    <div class="st">Datos del caso</div>
    <div class="field">
      <label>N° Certificado de fianza</label>
      <input id="cert" placeholder="Ej: AME20000730 / MCOR0001234 / B0145164"/>
    </div>
    <div class="field">
      <label>Tipo de programa</label>
      <select id="prog">
        <option value="">Seleccionar...</option>
        <option value="TRADICIONAL">Tradicional (MCOR… / AME…)</option>
        <option value="CHILEAPOYA">Chile Apoya (B… / C…)</option>
      </select>
    </div>
    <div class="field">
      <label>% Cobertura FOGAPE</label>
      <select id="cob">
        <option value="">Seleccionar...</option>
        <option>50</option><option>60</option><option>70</option>
        <option>80</option><option>85</option><option>90</option><option>95</option>
      </select>
    </div>
    <div class="field">
      <label>Monto fianza referencia ($CLP)</label>
      <input id="monto" type="number" placeholder="Ej: 15000000"/>
    </div>
    <div class="field">
      <label>¿Amortizaciones aplicadas?</label>
      <select id="amort" onchange="document.getElementById('ar_row').style.display=this.value==='si'?'flex':'none'">
        <option value="no">No</option>
        <option value="si">Sí</option>
      </select>
    </div>
    <div class="field" id="ar_row" style="display:none">
      <label>Monto amortizado ($CLP)</label>
      <input id="av" type="number" placeholder="Ej: 2500000"/>
    </div>
    <div class="field">
      <label>Rol causa judicial</label>
      <input id="rol" placeholder="Ej: C-13707-2024"/>
    </div>
    <div class="field">
      <label>Tribunal</label>
      <input id="trib" placeholder="Ej: 15° Juzgado Civil de Santiago"/>
    </div>
  </div>

  <div>
    <div class="st">Documentos del caso</div>
    <div class="drop-area" id="dropArea">
      <input type="file" accept=".pdf,.png,.jpg,.jpeg" multiple onchange="handleFiles(this.files)"/>
      <div class="drop-icon">📂</div>
      <div class="drop-label">Arrastra los archivos aquí</div>
      <div class="drop-hint">PDF, PNG o JPG · Múltiples archivos</div>
      <div class="drop-hint" style="margin-top:4px;color:#F47920;font-size:10px">
        PAGARE.pdf · LIQUIDACION.pdf · DEMANDA.pdf · MANDAMIENTO.pdf · etc.
      </div>
    </div>
    <div class="file-count" id="fileCount"></div>
    <div class="file-list" id="fileList"></div>
  </div>

  <div>
    <button class="btn" id="btnGo" onclick="go()">🔍 Iniciar auditoría de 44 puntos</button>
    <div class="pw" id="pw" style="display:none"><div class="pb" id="pb"></div></div>
  </div>

  <div class="log" id="log"></div>
</div>

<div class="right">
  <div class="empty" id="emp">
    <div class="ei">🛡️</div>
    <div class="eh2">Auditor FOGAPE listo</div>
    <p class="ep">Ingresa tu API Key, arrastra los documentos del caso, completa los datos y presiona "Iniciar auditoría".</p>
    <div class="grid2">
      <div class="mc"><strong>📋 Bloques 1–2</strong>Identificación · Crédito base</div>
      <div class="mc"><strong>📄 Bloque 3</strong>Fianza · Pagaré</div>
      <div class="mc"><strong>💰 Bloque 4</strong>Impagos · SAFIO</div>
      <div class="mc"><strong>⚖️ Bloque 5</strong>Control judicial</div>
    </div>
  </div>
  <div id="rep" style="display:none;flex-direction:column;gap:14px"></div>
</div>
</div>

<script>
if(window['pdfjs-dist/build/pdf']){
  window['pdfjs-dist/build/pdf'].GlobalWorkerOptions.workerSrc=
  'https://cdnjs.cloudflare.com/ajax/libs/pdf.js/3.11.174/pdf.worker.min.js';
}

const FILES = {};
const FILES_B64 = {};

// Drag and drop
const dropArea = document.getElementById('dropArea');
dropArea.addEventListener('dragover', e => { e.preventDefault(); dropArea.classList.add('drag'); });
dropArea.addEventListener('dragleave', () => dropArea.classList.remove('drag'));
dropArea.addEventListener('drop', e => { e.preventDefault(); dropArea.classList.remove('drag'); handleFiles(e.dataTransfer.files); });

function handleFiles(fileList) {
  for (const f of fileList) {
    FILES[f.name] = f;
    toB64(f).then(b64 => { FILES_B64[f.name] = { name: f.name, type: f.type, b64 }; });
  }
  renderFileList();
}

function renderFileList() {
  const list = document.getElementById('fileList');
  const count = document.getElementById('fileCount');
  const names = Object.keys(FILES);
  count.textContent = names.length > 0 ? `${names.length} archivo${names.length>1?'s':''} cargado${names.length>1?'s':''}` : '';
  list.innerHTML = names.map(name => {
    const size = (FILES[name].size / 1024).toFixed(0);
    const icon = name.toLowerCase().endsWith('.pdf') ? '📄' : '🖼️';
    return `<div class="file-item">
      <span class="file-icon">${icon}</span>
      <span class="fi-name" title="${name}">${name}</span>
      <span class="fi-size">${size} KB</span>
      <button class="fi-del" onclick="removeFile('${name}')" title="Quitar">✕</button>
    </div>`;
  }).join('');
}

function removeFile(name) {
  delete FILES[name];
  delete FILES_B64[name];
  renderFileList();
}

function toB64(f) {
  return new Promise(r => {
    const rd = new FileReader();
    rd.onload = () => r(rd.result.split(',')[1]);
    rd.readAsDataURL(f);
  });
}

function lg(msg, t='info') {
  const el = document.getElementById('log');
  el.style.display = 'block';
  const s = document.createElement('span');
  s.className = t==='ok'?'lok':t==='err'?'lerr':t==='warn'?'lwarn':'linfo';
  s.textContent = (t==='ok'?'✓ ':t==='err'?'✗ ':t==='warn'?'⚠ ':'→ ') + msg + '\n';
  el.appendChild(s);
  el.scrollTop = el.scrollHeight;
}

function sp(p) { document.getElementById('pb').style.width = p + '%'; }

async function pdfToImgs(b64) {
  return new Promise(async res => {
    try {
      const lib = window['pdfjs-dist/build/pdf'];
      if (!lib) { res([]); return; }
      const arr = new Uint8Array(atob(b64).split('').map(c => c.charCodeAt(0)));
      const pdf = await lib.getDocument({ data: arr }).promise;
      const imgs = [];
      const maxP = Math.min(pdf.numPages, 4);
      for (let i = 1; i <= maxP; i++) {
        const page = await pdf.getPage(i);
        const vp = page.getViewport({ scale: 1.8 });
        const cv = document.createElement('canvas');
        cv.width = vp.width; cv.height = vp.height;
        await page.render({ canvasContext: cv.getContext('2d'), viewport: vp }).promise;
        imgs.push(cv.toDataURL('image/jpeg', 0.85).split(',')[1]);
      }
      res(imgs);
    } catch(e) { res([]); }
  });
}

async function go() {
  const apikey = document.getElementById('ak').value.trim();
  if (!apikey) { alert('Ingresa tu API Key de OpenAI.'); return; }
  if (!apikey.startsWith('sk-')) { alert('La key debe comenzar con sk-'); return; }
  if (Object.keys(FILES).length === 0) { alert('Arrastra al menos un documento.'); return; }

  const btn = document.getElementById('btnGo');
  btn.disabled = true;
  btn.innerHTML = '<div class="spin"></div><span>Analizando...</span>';
  document.getElementById('pw').style.display = 'block';
  sp(5);
  document.getElementById('emp').style.display = 'none';
  const repEl = document.getElementById('rep');
  repEl.style.display = 'flex';
  repEl.innerHTML = '<div style="color:#888780;font-size:13px;padding:20px 0">Procesando documentos con GPT-4o...</div>';

  const cert  = document.getElementById('cert').value || 'No especificado';
  const prog  = document.getElementById('prog').value || 'No especificado';
  const cob   = document.getElementById('cob').value || 'No especificado';
  const monto = document.getElementById('monto').value;
  const conA  = document.getElementById('amort').value === 'si';
  const aval  = document.getElementById('av').value;
  const rol   = document.getElementById('rol').value || 'No especificado';
  const trib  = document.getElementById('trib').value || 'No especificado';

  lg('Iniciando auditoría — ' + cert);
  lg('Documentos: ' + Object.keys(FILES).join(', '));

  const content = [];
  content.push({ type: 'text', text: buildPrompt(cert, prog, cob, monto, conA, aval, rol, trib) });

  sp(15);
  let dc = 0;
  const td = Object.keys(FILES_B64).length;

  for (const [name, d] of Object.entries(FILES_B64)) {
    dc++;
    sp(15 + (dc / td) * 40);
    lg('Procesando: ' + name);
    content.push({ type: 'text', text: `\n\n=== ${name} ===` });

    if (d.type && d.type.startsWith('image/')) {
      content.push({ type: 'image_url', image_url: { url: `data:${d.type};base64,${d.b64}`, detail: 'high' } });
    } else if (d.type === 'application/pdf') {
      const imgs = await pdfToImgs(d.b64);
      if (imgs.length > 0) {
        lg('  ' + name + ' → ' + imgs.length + ' página(s)');
        for (const img of imgs) {
          content.push({ type: 'image_url', image_url: { url: `data:image/jpeg;base64,${img}`, detail: 'high' } });
        }
      } else {
        content.push({ type: 'text', text: `[PDF: ${name}]` });
        lg('  Sin conversión: ' + name, 'warn');
      }
    }
  }

  sp(60);
  lg('Enviando a GPT-4o...');

  try {
    const res = await fetch('https://api.openai.com/v1/chat/completions', {
      method: 'POST',
      headers: { 'Content-Type': 'application/json', 'Authorization': 'Bearer ' + apikey },
      body: JSON.stringify({
        model: 'gpt-4o',
        max_tokens: 8000,
        temperature: 0.1,
        messages: [
          { role: 'system', content: 'Eres Auditor Senior FOGAPE Chile con 15 años de experiencia en cobranza judicial. Responde ÚNICAMENTE con JSON válido, sin markdown ni texto extra.' },
          { role: 'user', content }
        ]
      })
    });

    sp(85);
    if (!res.ok) {
      const e = await res.json().catch(() => ({}));
      throw new Error(e?.error?.message || 'Error ' + res.status);
    }

    const data = await res.json();
    lg('Análisis completado.', 'ok');
    sp(95);

    const raw = data.choices?.[0]?.message?.content || '';
    let result;
    try {
      result = JSON.parse(raw.replace(/```json|```/g, '').trim());
    } catch(e) {
      throw new Error('Error parseando respuesta. Intenta nuevamente.');
    }

    sp(100);
    render(result);
    lg('Reporte generado con éxito.', 'ok');

  } catch(err) {
    lg(err.message, 'err');
    repEl.innerHTML = `<div style="background:#fcebeb;border-radius:10px;border:1px solid #f7c1c1;padding:18px 20px">
      <div style="font-weight:500;color:#791f1f;margin-bottom:8px">⚠ Error</div>
      <div style="font-size:12px;color:#501313">${err.message}</div>
      <div style="font-size:11px;color:#791f1f;margin-top:8px">Verifica que tu API Key sea válida con acceso a gpt-4o.</div>
    </div>`;
  } finally {
    btn.disabled = false;
    btn.innerHTML = '🔍 Nueva auditoría';
    setTimeout(() => { document.getElementById('pw').style.display = 'none'; sp(0); }, 1500);
  }
}

function buildPrompt(cert, prog, cob, monto, conA, aval, rol, trib) {
  return `Eres Auditor Senior FOGAPE. Analiza TODOS los documentos adjuntos cruzando información entre ellos exhaustivamente.

DATOS DEL CASO:
- Certificado: ${cert}
- Programa: ${prog} ${prog==='TRADICIONAL'?'(terminan en MCOR o AME)':prog==='CHILEAPOYA'?'(inician con B o C)':''}
- Cobertura FOGAPE: ${cob}%
- Monto referencia: ${monto ? '$' + Number(monto).toLocaleString('es-CL') : 'No ingresado'}
- Amortizaciones: ${conA ? 'SÍ — monto amortizado: $' + Number(aval||0).toLocaleString('es-CL') : 'No'}
- Rol judicial: ${rol}
- Tribunal: ${trib}
- Plazo máximo legal: 425 días desde primera cuota impaga

DOCUMENTOS POSIBLES EN ESTA CARPETA:
CARPETA TRIBUTARIA.pdf → Bloque 1: identificación SII
CERTIF DE FIANZA.pdf → Bloque 2 y 3: certificado y fianza
PAGARE.pdf → Bloque 3: pagaré original
MUTUO.pdf → Bloque 2: crédito base
CONTRATO DE GARANTIA.pdf → Bloque 2: garantía
LIQUIDACION.pdf → Bloque 4: saldos e impagos
CERTIF DE SAFIO.pdf → Bloque 4: estado SAFIO
PAGOS.pdf → Bloque 4: recuperación previa
DEMANDA.pdf → Bloque 5: control judicial
CERTIF DE DEMANDA.pdf → Bloque 5: calce procesal
MANDAMIENTO.pdf → Bloque 5: mandamiento FEA
NOTIFICACION.pdf → Bloque 5: certificación notificación
REQUERIMIENTO DE PAGO.pdf → Bloque 5: requerimiento
DECLARACION JURADA.pdf → Bloque 3: documentación legal
Carta Aclaratoria TRADICIONAL.pdf → Bloque 2: aclaratorias

PUNTOS CRÍTICOS A DETECTAR:
1. Monto Anexo 4 debe descontar amortizaciones si las hay
2. RUT sin errores tipográficos entre documentos
3. Montos consistentes entre pagaré, liquidación y certificado de fianza
4. No más de 425 días desde primera cuota impaga hasta hoy
5. Mandamiento debe tener FEA vigente
6. Petitorio de la demanda debe calzar exactamente con el monto del certificado
7. ALERTA INMEDIATA si la demanda menciona pagos parciales de MásAVAL
8. Cobertura % aplicada debe corresponder al programa declarado

Responde SOLO con este JSON exacto:
{
  "cliente": "Nombre extraído de los documentos",
  "rut": "RUT del cliente",
  "rol": "${rol}",
  "veredicto": "APROBADO | RECHAZADO | PENDIENTE CON ALERTA",
  "resumen_ejecutivo": "2-3 oraciones con veredicto y problemas principales",
  "puntos": [
    {"bloque":1,"numero":1,"nombre":"Validación Nombre/Razón Social","estado":"CONCORDE|ERROR|ALERTA|PENDIENTE","sustento":"..."},
    {"bloque":1,"numero":2,"nombre":"Validación RUT carácter a carácter","estado":"...","sustento":"..."},
    {"bloque":1,"numero":3,"nombre":"Actividad Económica SII","estado":"...","sustento":"..."},
    {"bloque":1,"numero":4,"nombre":"Tramo de Ventas SII","estado":"...","sustento":"..."},
    {"bloque":1,"numero":5,"nombre":"Elegibilidad técnica FOGAPE","estado":"...","sustento":"..."},
    {"bloque":2,"numero":6,"nombre":"Código operación SAFIO","estado":"...","sustento":"..."},
    {"bloque":2,"numero":7,"nombre":"Moneda de la operación","estado":"...","sustento":"..."},
    {"bloque":2,"numero":8,"nombre":"Monto Capital Original","estado":"...","sustento":"..."},
    {"bloque":2,"numero":9,"nombre":"Fecha Curse/Colocación","estado":"...","sustento":"..."},
    {"bloque":2,"numero":10,"nombre":"Tasa Cobertura FOGAPE (%)","estado":"...","sustento":"..."},
    {"bloque":2,"numero":11,"nombre":"Monto total Garantía FOGAPE","estado":"...","sustento":"..."},
    {"bloque":3,"numero":12,"nombre":"Fecha pago fianza MásAVAL","estado":"...","sustento":"..."},
    {"bloque":3,"numero":13,"nombre":"Monto líquido pagado fianza","estado":"...","sustento":"..."},
    {"bloque":3,"numero":14,"nombre":"Fecha vencimiento Pagaré","estado":"...","sustento":"..."},
    {"bloque":3,"numero":15,"nombre":"Fecha suscripción Pagaré","estado":"...","sustento":"..."},
    {"bloque":3,"numero":16,"nombre":"Monto Pagaré suscrito","estado":"...","sustento":"..."},
    {"bloque":3,"numero":17,"nombre":"Lugar suscripción","estado":"...","sustento":"..."},
    {"bloque":3,"numero":18,"nombre":"Avales y codeudores solidarios","estado":"...","sustento":"..."},
    {"bloque":3,"numero":19,"nombre":"Cláusula de aceleración","estado":"...","sustento":"..."},
    {"bloque":3,"numero":20,"nombre":"Impuesto Timbres y Estampillas","estado":"...","sustento":"..."},
    {"bloque":3,"numero":21,"nombre":"Interés penal pactado","estado":"...","sustento":"..."},
    {"bloque":3,"numero":22,"nombre":"Calce monto demandado vs saldo insoluto","estado":"...","sustento":"..."},
    {"bloque":4,"numero":23,"nombre":"Fecha primera cuota impaga","estado":"...","sustento":"..."},
    {"bloque":4,"numero":24,"nombre":"Cuotas totales vs impagas","estado":"...","sustento":"..."},
    {"bloque":4,"numero":25,"nombre":"Estado operación SAFIO","estado":"...","sustento":"..."},
    {"bloque":4,"numero":26,"nombre":"Saldo insoluto capital al default","estado":"...","sustento":"..."},
    {"bloque":4,"numero":27,"nombre":"Intereses corrientes devengados","estado":"...","sustento":"..."},
    {"bloque":4,"numero":28,"nombre":"Intereses penales/mora","estado":"...","sustento":"..."},
    {"bloque":4,"numero":29,"nombre":"Comisiones/seguros","estado":"...","sustento":"..."},
    {"bloque":4,"numero":30,"nombre":"Monto neto pérdida","estado":"...","sustento":"..."},
    {"bloque":4,"numero":31,"nombre":"% recuperación previa","estado":"...","sustento":"..."},
    {"bloque":4,"numero":32,"nombre":"Gastos cobranza extrajudicial","estado":"...","sustento":"..."},
    {"bloque":5,"numero":33,"nombre":"Identificación exacta Tribunal","estado":"...","sustento":"..."},
    {"bloque":5,"numero":34,"nombre":"Número Rol causa judicial","estado":"...","sustento":"..."},
    {"bloque":5,"numero":35,"nombre":"Fecha presentación Demanda","estado":"...","sustento":"..."},
    {"bloque":5,"numero":36,"nombre":"Fecha resolución Mandamiento","estado":"...","sustento":"..."},
    {"bloque":5,"numero":37,"nombre":"Calce petitorio demanda vs certificado fianza","estado":"...","sustento":"..."},
    {"bloque":5,"numero":38,"nombre":"ALERTA pagos parciales MásAVAL en demanda","estado":"...","sustento":"..."},
    {"bloque":5,"numero":39,"nombre":"Certificación notificación deudor","estado":"...","sustento":"..."},
    {"bloque":5,"numero":40,"nombre":"Certificación requerimiento de pago","estado":"...","sustento":"..."},
    {"bloque":5,"numero":41,"nombre":"Estado embargo/bienes","estado":"...","sustento":"..."},
    {"bloque":5,"numero":42,"nombre":"Costas personales juicio","estado":"...","sustento":"..."},
    {"bloque":5,"numero":43,"nombre":"Costas procesales juicio","estado":"...","sustento":"..."},
    {"bloque":5,"numero":44,"nombre":"Mandamiento con FEA vigente","estado":"...","sustento":"..."}
  ],
  "observaciones_criticas": [
    {"tipo":"ERROR|ALERTA|INFO","titulo":"...","detalle":"Explicación detallada con acción correctiva específica"}
  ]
}`;
}

function render(r) {
  const repEl = document.getElementById('rep');
  const pts = r.puntos || [];
  const obs = r.observaciones_criticas || [];
  const ok   = pts.filter(p => p.estado==='CONCORDE').length;
  const err  = pts.filter(p => p.estado==='ERROR').length;
  const warn = pts.filter(p => p.estado==='ALERTA').length;
  const pend = pts.filter(p => p.estado==='PENDIENTE').length;
  const ev   = ok + err + warn;
  const pct  = ev > 0 ? Math.round(ok / ev * 100) : 0;
  const sc   = pct >= 80 ? '#639922' : pct >= 60 ? '#ba7517' : '#a32d2d';
  const vc   = r.veredicto?.includes('APROBADO') && !r.veredicto?.includes('PENDIENTE') ? 'A'
             : r.veredicto?.includes('RECHAZADO') ? 'R' : 'P';

  const bloques = [
    {n:1,t:'Identificación del cliente y configuración del caso',r:[1,5]},
    {n:2,t:'Financiamiento original y crédito base',r:[6,11]},
    {n:3,t:'Hitos de cobro, fianza y pagaré',r:[12,22]},
    {n:4,t:'Línea de impagos y estado en SAFIO',r:[23,32]},
    {n:5,t:'Control judicial y calce procesal',r:[33,44]}
  ];

  let h = `
  <div class="ar">
    <button class="bsm" onclick="exportRep()">⬇ Exportar HTML</button>
    <button class="bsm" onclick="window.print()">🖨 Imprimir</button>
  </div>
  <div class="rhead">
    <div style="display:flex;align-items:center;gap:10px;flex-wrap:wrap;margin-bottom:10px">
      <div style="font-size:16px;font-weight:500;flex:1">${r.cliente||'Cliente'}</div>
      <div class="vb v${vc}">${r.veredicto||'PENDIENTE CON ALERTA'}</div>
    </div>
    <div style="font-size:12px;color:#5f5e5a;line-height:1.6;margin-bottom:12px">${r.resumen_ejecutivo||''}</div>
    <div class="rmeta">
      <div class="rmi"><div class="rml">RUT</div><div class="rmv">${r.rut||'—'}</div></div>
      <div class="rmi"><div class="rml">Rol causa</div><div class="rmv">${r.rol||'—'}</div></div>
      <div class="rmi"><div class="rml">Certificado</div><div class="rmv">${document.getElementById('cert').value||'—'}</div></div>
    </div>
    <div class="srow">
      <div style="font-size:11px;color:#5f5e5a;min-width:72px">Concordancia</div>
      <div class="sbar"><div class="sfill" style="width:${pct}%;background:${sc}"></div></div>
      <div style="font-size:12px;font-weight:500;min-width:36px;text-align:right;color:${sc}">${pct}%</div>
    </div>
    <div style="display:flex;gap:12px;margin-top:8px;font-size:11px;flex-wrap:wrap">
      <span style="color:#27500a">✓ ${ok} concordes</span>
      <span style="color:#791f1f">✗ ${err} errores</span>
      <span style="color:#633806">⚠ ${warn} alertas</span>
      ${pend>0?`<span style="color:#5f5e5a">○ ${pend} pendientes</span>`:''}
    </div>
  </div>`;

  for (const b of bloques) {
    const bp = pts.filter(p => p.numero >= b.r[0] && p.numero <= b.r[1]);
    const be = bp.filter(p => p.estado==='ERROR').length;
    const bw = bp.filter(p => p.estado==='ALERTA').length;
    const bo = bp.filter(p => p.estado==='CONCORDE').length;
    h += `
    <div class="rb">
      <div class="rbh" onclick="tb(${b.n})">
        <div style="font-size:12px;color:#888780;min-width:22px;font-weight:500">B${b.n}</div>
        <div class="rbht">${b.t}</div>
        <div class="pills">
          ${bo>0?`<span class="pill pok">✓ ${bo}</span>`:''}
          ${be>0?`<span class="pill perr">✗ ${be}</span>`:''}
          ${bw>0?`<span class="pill pwarn">⚠ ${bw}</span>`:''}
        </div>
        <div class="chev open" id="ch_${b.n}">▼</div>
      </div>
      <div class="rbb open" id="bd_${b.n}">
        <table class="at">
          <thead><tr>
            <th style="width:32px">#</th>
            <th>Punto de control</th>
            <th style="width:100px">Estado</th>
            <th>Sustento documental</th>
          </tr></thead>
          <tbody>`;
    for (const p of bp) {
      const ec = p.estado==='CONCORDE'?'C':p.estado==='ERROR'?'E':p.estado==='ALERTA'?'A':'P';
      h += `<tr>
        <td style="color:#888780;font-size:11px">${p.numero}</td>
        <td style="font-weight:500">${p.nombre||''}</td>
        <td><span class="est e${ec}">${p.estado}</span></td>
        <td style="color:#5f5e5a">${p.sustento||'—'}</td>
      </tr>`;
    }
    h += `</tbody></table></div></div>`;
  }

  if (obs.length > 0) {
    h += `<div class="ob">
      <div style="font-size:13px;font-weight:500;margin-bottom:12px">
        ⚠ Observaciones críticas
        <span style="font-size:11px;font-weight:400;color:#888780">(${obs.length})</span>
      </div>`;
    for (const o of obs) {
      const oc = o.tipo==='ERROR'?'E':o.tipo==='ALERTA'?'A':'I';
      h += `<div class="oi o${oc}">
        <div class="ol">${o.tipo}: ${o.titulo}</div>
        <div>${o.detalle}</div>
      </div>`;
    }
    h += '</div>';
  }

  repEl.innerHTML = h;
  window._lr = r;
}

function tb(n) {
  document.getElementById('bd_'+n).classList.toggle('open');
  document.getElementById('ch_'+n).classList.toggle('open');
}

function exportRep() {
  if (!window._lr) return;
  const cert = document.getElementById('cert').value || 'caso';
  const c = document.getElementById('rep').innerHTML;
  const html = `<!DOCTYPE html><html lang="es"><head><meta charset="UTF-8">
<title>Reporte FOGAPE — ${cert}</title>
<style>body{font-family:sans-serif;margin:28px;color:#1a1a18;font-size:13px}
h1{font-size:20px;margin-bottom:4px}.sub{color:#888780;font-size:12px;margin-bottom:20px}
table{width:100%;border-collapse:collapse}th,td{padding:8px 12px;border:1px solid #e5e4df;text-align:left;vertical-align:top}
th{background:#f5f5f3;font-size:11px;font-weight:500;color:#888780}
.est{display:inline-block;padding:2px 8px;border-radius:4px;font-size:10px;font-weight:500}
.eC{background:#eaf3de;color:#27500a}.eE{background:#fcebeb;color:#791f1f}
.eA{background:#faeeda;color:#633806}.eP{background:#f1efe8;color:#5f5e5a}
.vb{display:inline-block;padding:5px 14px;border-radius:14px;font-size:13px;font-weight:500}
.vA{background:#eaf3de;color:#27500a}.vR{background:#fcebeb;color:#791f1f}.vP{background:#faeeda;color:#633806}
.rb{border:1px solid #e5e4df;border-radius:8px;margin-bottom:14px;page-break-inside:avoid}
.rbh{padding:10px 14px;background:#f5f5f3;font-size:13px;font-weight:500}
.rbb{display:block!important}
.ob{border:1px solid #e5e4df;border-radius:8px;padding:16px;margin-bottom:14px}
.oi{padding:10px 12px;border-radius:6px;border-left:3px solid;margin-bottom:8px;font-size:12px;line-height:1.55}
.oE{background:#fcebeb;border-color:#e24b4a;color:#501313}
.oA{background:#faeeda;border-color:#ef9f27;color:#412402}
.oI{background:#e6f1fb;border-color:#378add;color:#042c53}
.ol{font-weight:500;font-size:11px;margin-bottom:3px}
.rhead{border:1px solid #e5e4df;border-radius:8px;padding:16px;margin-bottom:14px}
.ar,.bsm,.chev,.pills,.sbar,.srow,.pw,.rmeta{display:none!important}
</style></head><body>
<h1>Reporte Auditoría FOGAPE</h1>
<div class="sub">${new Date().toLocaleString('es-CL')} · Certificado: ${cert} · Maxxa Cobranza Judicial</div>
${c}</body></html>`;
  const blob = new Blob([html], {type:'text/html'});
  const a = document.createElement('a');
  a.href = URL.createObjectURL(blob);
  a.download = `reporte_fogape_${cert.replace(/[^a-zA-Z0-9]/g,'_')}_${new Date().toISOString().slice(0,10)}.html`;
  a.click();
}
</script>
</body>
</html>
