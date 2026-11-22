<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="robots" content="noindex, nofollow">
<meta name="theme-color" content="#07140d">
<title>Puro Trato Rações - Catálogo Digital</title>
<link rel="preconnect" href="https://www.gstatic.com" crossorigin>
<link rel="preconnect" href="https://firestore.googleapis.com" crossorigin>
<style>
:root{--d:#0b1f14;--dd:#07140d;--g:#d4af37;--t:#f3f4f6;--m:#9ca3af}
*{box-sizing:border-box}
body{margin:0;background:var(--d);color:var(--t);font-family:system-ui,-apple-system,"Segoe UI",Roboto,Arial,sans-serif;min-height:100vh;display:flex;flex-direction:column}
.hidden{display:none!important}
button,input,select{font:inherit}
button{cursor:pointer}
header{background:var(--dd);border-bottom:1px solid var(--g);position:sticky;top:0;z-index:40;box-shadow:0 4px 12px #0006}
.wrap{max-width:72rem;margin:0 auto;padding:1rem}
.row{display:flex;align-items:center;gap:.75rem}
.between{justify-content:space-between}
.logo{width:48px;height:48px;border-radius:50%;border:2px solid var(--g);object-fit:cover;background:var(--d)}
h1{margin:0;font-size:1.5rem;font-weight:900;color:var(--g);letter-spacing:.03em}
.sub{margin:0;font-size:.7rem;color:var(--m);letter-spacing:.1em}
.btn{background:var(--g);color:#000;font-weight:700;border:0;border-radius:.5rem;padding:.6rem 1rem;font-size:.85rem;white-space:nowrap}
.btn:hover{opacity:.9}.btn:disabled{opacity:.5;cursor:wait}
.btn.o{background:var(--d);color:var(--g);border:1px solid var(--g)}
.btn.o:hover{background:var(--g);color:#000}
.btn.r{background:#dc262633;color:#f87171;border:1px solid #ef444455;font-size:.75rem;padding:.35rem .75rem}
.btn.r:hover{background:#dc2626;color:#fff}
.btn.b{background:#2563eb33;color:#60a5fa;border:1px solid #3b82f655;font-size:.75rem;padding:.35rem .75rem}
.btn.b:hover{background:#2563eb;color:#fff}
.box{background:var(--dd);border:1px solid #d4af3744;border-radius:.75rem;padding:1.25rem;margin-bottom:1.5rem;box-shadow:0 10px 25px #0005}
.box h2,.box h3{color:var(--g);margin:0 0 .75rem}
.small{font-size:.8rem;color:#d1d5db;margin:.2rem 0}
.tag{border:1px solid var(--g);color:var(--g);background:#d4af3718;padding:.5rem 1rem;border-radius:.5rem;font-size:.75rem;font-weight:600}
.inp{width:100%;background:var(--d);border:1px solid #d4af3766;border-radius:.5rem;padding:.65rem;color:#fff;font-size:.875rem}
.inp:focus{outline:2px solid var(--g);outline-offset:0}
label{display:block;font-size:.75rem;color:#d1d5db;margin-bottom:.25rem}
.g2{display:grid;grid-template-columns:1fr;gap:1rem;margin-bottom:1rem}
@media(min-width:640px){.g2{grid-template-columns:1fr 1fr}}
.bar{display:flex;flex-direction:column;gap:1rem;margin-bottom:1.5rem}
@media(min-width:640px){.bar{flex-direction:row;justify-content:space-between;align-items:center}}
.cats{display:flex;gap:.5rem;overflow-x:auto;padding-bottom:.5rem;scrollbar-width:none}
.cats::-webkit-scrollbar{display:none}
.cat{background:var(--dd);border:1px solid #d4af3780;color:#d1d5db;padding:.4rem .9rem;border-radius:.5rem;font-size:.75rem;font-weight:700;white-space:nowrap}
.cat.on{background:var(--g);color:#000;border-color:var(--g)}
#grid{display:grid;grid-template-columns:repeat(3,1fr);gap:.5rem}
@media(min-width:640px){#grid{gap:1.5rem}}
@media(min-width:768px){#grid{grid-template-columns:repeat(4,1fr)}}
@media(min-width:1024px){#grid{grid-template-columns:repeat(5,1fr)}}
.full{grid-column:1/-1;text-align:center;padding:3rem 0;color:var(--m)}
.p{background:var(--dd);border:1px solid #d4af3744;border-radius:.5rem;overflow:hidden;display:flex;flex-direction:column;justify-content:space-between;content-visibility:auto;contain-intrinsic-size:200px 180px}
.p:hover{border-color:var(--g)}
.p .im{height:80px;background:#111;position:relative}
.p img{width:100%;height:100%;object-fit:cover;display:block}
.p .cat-tag{display:none;position:absolute;top:8px;right:8px;background:#0b1f14cc;border:1px solid var(--g);color:var(--g);font-size:10px;font-weight:700;padding:3px 10px;border-radius:99px;text-transform:uppercase;max-width:80%;overflow:hidden;text-overflow:ellipsis;white-space:nowrap}
.p h3{margin:0;padding:.5rem .5rem .25rem;font-size:10px;line-height:1.2;display:-webkit-box;-webkit-line-clamp:2;-webkit-box-orient:vertical;overflow:hidden}
.p .pr{padding:0 .5rem .5rem;color:var(--g);font-weight:900;font-size:.75rem}
@media(min-width:640px){.p .im{height:128px}.p .cat-tag{display:block}.p h3{font-size:.875rem;padding:1rem 1rem .25rem}.p .pr{padding:0 1rem 1rem;font-size:1rem}}
@media(min-width:768px){.p .im{height:192px}.p h3{font-size:1rem}.p .pr{font-size:1.125rem}}
.spin{display:inline-block;width:24px;height:24px;border:3px solid #d4af3744;border-top-color:var(--g);border-radius:50%;animation:s .8s linear infinite}
@keyframes s{to{transform:rotate(360deg)}}
@media(prefers-reduced-motion:reduce){.spin{animation-duration:2s}}
footer{background:var(--dd);border-top:1px solid #d4af3744;margin-top:3rem;padding:1.5rem 1rem;text-align:center;font-size:.75rem;color:var(--m)}
footer p{margin:.25rem 0}
.modal{position:fixed;inset:0;background:#000c;z-index:60;display:flex;align-items:center;justify-content:center;padding:1rem}
.modal .box{max-width:24rem;width:100%;margin:0;position:relative;background:var(--d);border-color:var(--g)}
.x{position:absolute;top:.75rem;right:1rem;background:none;border:0;color:var(--m);font-size:1.25rem}
.item{background:var(--d);border:1px solid #d4af3744;padding:.75rem;border-radius:.5rem;display:flex;justify-content:space-between;align-items:center;gap:.5rem;font-size:.875rem}
.item .info{display:flex;align-items:center;gap:.75rem;min-width:0}
.item img{width:40px;height:40px;object-fit:cover;border-radius:.375rem;border:1px solid #d4af3766}
.item .txt{min-width:0}.item b,.item small{display:block;overflow:hidden;text-overflow:ellipsis;white-space:nowrap}
.item small{color:var(--g);font-size:.75rem;font-weight:600}
.chips{display:flex;flex-wrap:wrap;gap:.5rem}
.chip{background:var(--d);border:1px solid #d4af3744;padding:.35rem .75rem;border-radius:.5rem;display:flex;align-items:center;gap:.5rem;font-size:.75rem;font-weight:600}
.chip button{background:none;border:0;color:#f87171}
#lista{display:grid;gap:.5rem;max-height:24rem;overflow-y:auto;padding-right:.5rem}
.toast{position:fixed;bottom:1rem;left:50%;transform:translateX(-50%);background:var(--g);color:#000;font-weight:700;padding:.6rem 1.2rem;border-radius:.5rem;z-index:80;font-size:.85rem;box-shadow:0 6px 20px #0008}
</style>
</head>
<body>

<header>
  <div class="wrap row between" style="flex-wrap:wrap">
    <div class="row">
      <img class="logo" id="logoTopo" alt="Logo Puro Trato" width="48" height="48">
      <div><h1>PURO TRATO</h1><p class="sub">RAÇÕES E SUPRIMENTOS</p></div>
    </div>
    <button id="btnTopo" class="btn o" type="button">🔒 Área Restrita</button>
  </div>
</header>

<main id="vitrine" class="wrap" style="flex:1;width:100%;padding-top:2rem">
  <div class="box row between" style="flex-wrap:wrap;gap:1rem">
    <div>
      <h2 style="font-size:1.25rem">🏪 Bem-vindo à nossa Vitrine</h2>
      <p class="small" id="infoEnd"></p>
      <p class="small" id="infoWhats"></p>
    </div>
    <span class="tag">ℹ️ Vendas na Loja Física</span>
  </div>

  <div class="bar">
    <div class="row" style="gap:.5rem">
      <input id="busca" class="inp" type="search" placeholder="🔍 Pesquisar produto..." style="min-width:12rem;border-color:#d4af3780" autocomplete="off">
      <button id="btnEncarte" class="btn" type="button">🖼️ <span>Gerar Encarte</span></button>
    </div>
    <div id="filtros" class="cats"></div>
  </div>

  <div id="grid"><div class="full"><span class="spin"></span><p>Carregando produtos...</p></div></div>
</main>

<main id="admin" class="wrap hidden" style="flex:1;width:100%;max-width:56rem;padding-top:2rem">
  <div class="row between" style="border-bottom:1px solid #d4af3744;padding-bottom:1rem;margin-bottom:1.5rem">
    <h2 style="color:var(--g);margin:0;font-size:1.5rem">🛠️ Painel Administrativo</h2>
    <button id="btnSair" class="btn r" type="button">Sair do painel</button>
  </div>

  <div class="box">
    <h3>Informações e logotipo da loja</h3>
    <form id="formLoja">
      <div class="g2">
        <div><label for="cfgLogo">Logotipo (celular ou PC)</label><input class="inp" type="file" id="cfgLogo" accept="image/*"></div>
        <div class="row"><span class="small">Logo atual:</span><img id="logoAdmin" class="logo" alt="Logo atual"></div>
      </div>
      <div style="margin-bottom:1rem"><label for="cfgEnd">Endereço</label><input class="inp" id="cfgEnd" required></div>
      <div class="g2">
        <div><label for="cfgWhats">WhatsApp / telefones</label><input class="inp" id="cfgWhats" required></div>
        <div><label for="cfgDet">Detalhes de localização</label><input class="inp" id="cfgDet" required></div>
      </div>
      <button class="btn" id="btnLoja" type="submit">Salvar loja</button>
    </form>
  </div>

  <div class="box">
    <h3>Categorias</h3>
    <form id="formCat" class="row" style="margin-bottom:1rem;flex-wrap:wrap">
      <input class="inp" id="novaCat" placeholder="Nova categoria (ex.: Aves)" required style="flex:1;min-width:10rem">
      <button class="btn" type="submit">Adicionar categoria</button>
    </form>
    <div id="chips" class="chips"></div>
  </div>

  <div class="box">
    <div class="row between"><h3 id="tituloProd">Adicionar produto</h3><button id="btnCancel" class="hidden btn" type="button" style="background:none;color:var(--m);text-decoration:underline">Cancelar edição</button></div>
    <form id="formProd" style="background:var(--d);padding:1rem;border-radius:.75rem;border:1px solid #d4af3733;margin-bottom:1.5rem">
      <input type="hidden" id="pId"><input type="hidden" id="pFotoAtual">
      <div class="g2">
        <div><label for="pNome">Nome do produto</label><input class="inp" id="pNome" placeholder="Ex.: Ração X Adulto 15kg" required></div>
        <div><label for="pPreco">Preço (R$)</label><input class="inp" id="pPreco" type="number" step="0.01" min="0" placeholder="89.90" required></div>
      </div>
      <div class="g2">
        <div><label for="pCat">Categoria</label><select class="inp" id="pCat" required></select></div>
        <div><label for="pFoto">Foto (celular ou PC)</label><input class="inp" id="pFoto" type="file" accept="image/*"></div>
      </div>
      <button class="btn" id="btnProd" type="submit" style="width:100%">Cadastrar produto</button>
    </form>
    <h4 style="color:var(--g);margin:0 0 .75rem">Produtos cadastrados</h4>
    <div id="lista"></div>
  </div>
</main>

<footer>
  <p>Puro Trato Rações &copy; 2026 - Todos os direitos reservados</p>
  <p id="footDet"></p>
</footer>

<div id="modalLogin" class="modal hidden" role="dialog" aria-modal="true" aria-label="Login administrativo">
  <form id="formLogin" class="box">
    <button class="x" type="button" id="fechaLogin" aria-label="Fechar">✕</button>
    <h3>🔒 Área administrativa</h3>
    <div style="margin-bottom:1rem"><label for="user">Usuário</label><input class="inp" id="user" autocomplete="username"></div>
    <div style="margin-bottom:1rem"><label for="pass">Senha</label><input class="inp" id="pass" type="password" autocomplete="current-password"></div>
    <button class="btn" type="submit" style="width:100%">Entrar</button>
  </form>
</div>

<script type="module">
import { initializeApp } from "https://www.gstatic.com/firebasejs/10.8.0/firebase-app.js";
import { getFirestore, collection, getDocs, addDoc, updateDoc, deleteDoc, doc, getDoc, setDoc } from "https://www.gstatic.com/firebasejs/10.8.0/firebase-firestore.js";

const db = getFirestore(initializeApp({
  apiKey: "AIzaSyDjSD3RhWOxL0TAB9XMAcX2S9BXHTUBkjs",
  authDomain: "puro-trato-catalogo.firebaseapp.com",
  projectId: "puro-trato-catalogo",
  storageBucket: "puro-trato-catalogo.firebasestorage.app",
  messagingSenderId: "676239897412",
  appId: "1:676239897412:web:dce3222a2494ad49d15d11"
}));

const $ = id => document.getElementById(id);
const esc = s => String(s ?? '').replace(/[&<>"']/g, c => ({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[c]));
const brl = n => 'R$ ' + Number(n || 0).toFixed(2).replace('.', ',');
const PLACEHOLDER = 'data:image/svg+xml;utf8,' + encodeURIComponent('<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><rect width="100" height="100" fill="#111c15"/><text x="50" y="62" font-size="40" text-anchor="middle">🐾</text></svg>');
const CACHE_KEY = 'pt_cache_v3';

let produtos = [], categorias = ["Cães", "Gatos", "Outros"], catAtual = 'todos', admin = false;
let cfg = {
  endereco: "Rua Orfeu Facchini, 39 B, Residencial Fabri, Salto-SP",
  whatsapp: "(15) 99793-6137 / (15) 99813-1628",
  detalhes: "Casa de esquina, sobrado cinza e preto | CEP: 13327-093",
  logo: PLACEHOLDER
};

function toast(msg) {
  const t = document.createElement('div');
  t.className = 'toast'; t.textContent = msg; t.setAttribute('role', 'status');
  document.body.appendChild(t); setTimeout(() => t.remove(), 2800);
}

function salvarCache() {
  try { localStorage.setItem(CACHE_KEY, JSON.stringify({ cfg, categorias, produtos })); } catch (e) {}
}
function lerCache() {
  try {
    const c = JSON.parse(localStorage.getItem(CACHE_KEY) || 'null');
    if (!c) return false;
    cfg = { ...cfg, ...c.cfg }; categorias = c.categorias || categorias; produtos = c.produtos || [];
    return produtos.length > 0;
  } catch (e) { return false; }
}

function renderConfig() {
  $('infoEnd').textContent = '📍 ' + cfg.endereco;
  $('infoWhats').textContent = '💬 ' + cfg.whatsapp;
  $('footDet').textContent = cfg.detalhes;
  $('logoTopo').src = cfg.logo || PLACEHOLDER;
  $('logoAdmin').src = cfg.logo || PLACEHOLDER;
  $('cfgEnd').value = cfg.endereco; $('cfgWhats').value = cfg.whatsapp; $('cfgDet').value = cfg.detalhes;
}

function renderCategorias() {
  $('filtros').innerHTML =
    `<button class="cat ${catAtual === 'todos' ? 'on' : ''}" data-cat="todos" type="button">Todos</button>` +
    categorias.map(c => `<button class="cat ${catAtual === c ? 'on' : ''}" data-cat="${esc(c)}" type="button">${esc(c)}</button>`).join('');
  $('pCat').innerHTML = categorias.map(c => `<option value="${esc(c)}">${esc(c)}</option>`).join('');
  $('chips').innerHTML = categorias.map(c => `<div class="chip"><span>${esc(c)}</span><button type="button" data-del-cat="${esc(c)}" aria-label="Excluir ${esc(c)}">✕</button></div>`).join('');
}

function filtrados() {
  const q = $('busca').value.trim().toLowerCase();
  const lista = produtos.filter(p => (catAtual === 'todos' || p.categoria === catAtual) && String(p.nome || '').toLowerCase().includes(q));
  if (catAtual === 'todos') lista.sort((a, b) => String(a.categoria || '').localeCompare(String(b.categoria || ''), 'pt-BR') || String(a.nome || '').localeCompare(String(b.nome || ''), 'pt-BR'));
  return lista;
}

function renderProdutos() {
  const l = filtrados();
  $('grid').innerHTML = l.length ? l.map((p, i) => `
    <article class="p">
      <div>
        <div class="im">
          <img src="${esc(p.foto || PLACEHOLDER)}" alt="${esc(p.nome)}" width="300" height="300" decoding="async" ${i < 6 ? 'fetchpriority="high"' : 'loading="lazy"'} data-fb>
          <span class="cat-tag">${esc(p.categoria)}</span>
        </div>
        <h3>${esc(p.nome)}</h3>
      </div>
      <div class="pr">${brl(p.preco)}</div>
    </article>`).join('') : '<div class="full">Nenhum produto encontrado.</div>';
}

function renderAdminLista() {
  $('lista').innerHTML = produtos.length ? produtos.map(p => `
    <div class="item">
      <div class="info">
        <img src="${esc(p.foto || PLACEHOLDER)}" alt="" width="40" height="40" loading="lazy" data-fb>
        <div class="txt"><b>${esc(p.nome)}</b><small>${brl(p.preco)} (${esc(p.categoria)})</small></div>
      </div>
      <div class="row" style="gap:.5rem;flex-shrink:0">
        <button class="btn b" type="button" data-edit="${esc(p.id)}">Editar</button>
        <button class="btn r" type="button" data-del="${esc(p.id)}">Excluir</button>
      </div>
    </div>`).join('') : '<p class="small">Nenhum produto cadastrado.</p>';
}

document.addEventListener('error', e => {
  const i = e.target;
  if (i.tagName === 'IMG' && i.hasAttribute('data-fb') && i.src !== PLACEHOLDER) i.src = PLACEHOLDER;
}, true);

async function carregarTudo() {
  try {
    const [cSnap, catSnap, pSnap] = await Promise.all([
      getDoc(doc(db, "configuracoes", "loja")),
      getDoc(doc(db, "configuracoes", "categorias")),
      getDocs(collection(db, "produtos"))
    ]);
    if (cSnap.exists()) cfg = { ...cfg, ...cSnap.data() };
    if (catSnap.exists() && Array.isArray(catSnap.data().lista)) categorias = catSnap.data().lista;
    else setDoc(doc(db, "configuracoes", "categorias"), { lista: categorias }).catch(() => {});
    produtos = pSnap.docs.map(d => ({ id: d.id, ...d.data() }));
    salvarCache();
    renderConfig(); renderCategorias(); renderProdutos(); renderAdminLista();
  } catch (err) {
    console.error("Erro ao carregar:", err);
    if (!produtos.length) $('grid').innerHTML = '<div class="full" style="color:#f87171">Não foi possível carregar os produtos. Verifique sua conexão e atualize a página.</div>';
  }
}

function comprimirImagem(file, max = 500) {
  return new Promise((resolve, reject) => {
    const url = URL.createObjectURL(file);
    const img = new Image();
    img.onload = () => {
      const r = Math.min(1, max / Math.max(img.width, img.height));
      const c = document.createElement('canvas');
      c.width = Math.round(img.width * r); c.height = Math.round(img.height * r);
      c.getContext('2d').drawImage(img, 0, 0, c.width, c.height);
      URL.revokeObjectURL(url);
      resolve(c.toDataURL('image/jpeg', 0.75));
    };
    img.onerror = () => { URL.revokeObjectURL(url); reject(new Error('Imagem inválida')); };
    img.src = url;
  });
}

let t;
$('busca').addEventListener('input', () => { clearTimeout(t); t = setTimeout(renderProdutos, 150); });
$('filtros').addEventListener('click', e => {
  const b = e.target.closest('[data-cat]'); if (!b) return;
  catAtual = b.dataset.cat; renderCategorias(); renderProdutos();
});

function mostrarAdmin(v) {
  $('vitrine').classList.toggle('hidden', v);
  $('admin').classList.toggle('hidden', !v);
  $('btnTopo').textContent = v ? '🏪 Ver Vitrine' : (admin ? '🛠️ Painel Admin' : '🔒 Área Restrita');
}

$('btnTopo').onclick = () => {
  if (!admin) { $('modalLogin').classList.remove('hidden'); $('user').focus(); }
  else mostrarAdmin($('admin').classList.contains('hidden'));
};

const fecharLogin = () => { $('modalLogin').classList.add('hidden'); $('formLogin').reset(); };
$('fechaLogin').onclick = fecharLogin;
$('modalLogin').addEventListener('click', e => { if (e.target.id === 'modalLogin') fecharLogin(); });
document.addEventListener('keydown', e => { if (e.key === 'Escape') fecharLogin(); });

$('formLogin').onsubmit = e => {
  e.preventDefault();
  if ($('user').value === 'puro trato' && $('pass').value === 'regianeeandre') {
    admin = true; fecharLogin(); mostrarAdmin(true); renderAdminLista();
  } else toast('Usuário ou senha incorretos');
};
$('btnSair').onclick = () => { admin = false; mostrarAdmin(false); };

$('formLoja').onsubmit = async e => {
  e.preventDefault();
  const btn = $('btnLoja'); btn.disabled = true; btn.textContent = 'Salvando...';
  try {
    const f = $('cfgLogo').files[0];
    const logo = f ? await comprimirImagem(f, 300) : cfg.logo;
    cfg = { endereco: $('cfgEnd').value, whatsapp: $('cfgWhats').value, detalhes: $('cfgDet').value, logo };
    await setDoc(doc(db, "configuracoes", "loja"), cfg);
    salvarCache(); renderConfig(); $('cfgLogo').value = ''; toast('Loja salva');
  } catch (err) { console.error(err); toast('Erro ao salvar a loja'); }
  finally { btn.disabled = false; btn.textContent = 'Salvar loja'; }
};

async function salvarCategorias() {
  await setDoc(doc(db, "configuracoes", "categorias"), { lista: categorias });
  salvarCache(); renderCategorias(); renderProdutos();
}

$('formCat').onsubmit = async e => {
  e.preventDefault();
  const n = $('novaCat').value.trim();
  if (!n) return;
  if (categorias.some(c => c.toLowerCase() === n.toLowerCase())) return toast('Essa categoria já existe');
  categorias.push(n);
  try { await salvarCategorias(); $('novaCat').value = ''; toast('Categoria adicionada'); }
  catch (err) { categorias.pop(); console.error(err); toast('Erro ao salvar categoria'); }
};

$('chips').addEventListener('click', async e => {
  const b = e.target.closest('[data-del-cat]'); if (!b) return;
  const nome = b.dataset.delCat;
  if (!confirm(`Excluir a categoria "${nome}"?`)) return;
  const antes = [...categorias];
  categorias = categorias.filter(c => c !== nome);
  if (catAtual === nome) catAtual = 'todos';
  try { await salvarCategorias(); } catch (err) { categorias = antes; renderCategorias(); toast('Erro ao excluir categoria'); }
});

function resetForm() {
  $('formProd').reset(); $('pId').value = ''; $('pFotoAtual').value = '';
  $('tituloProd').textContent = 'Adicionar produto';
  $('btnProd').textContent = 'Cadastrar produto';
  $('btnCancel').classList.add('hidden');
}
$('btnCancel').onclick = resetForm;

$('formProd').onsubmit = async e => {
  e.preventDefault();
  const btn = $('btnProd'), id = $('pId').value;
  const isEdicao = Boolean(id);
  btn.disabled = true; btn.textContent = 'Salvando...';
  try {
    const f = $('pFoto').files[0];
    const foto = f ? await comprimirImagem(f) : $('pFotoAtual').value;
    if (!foto) { toast('Selecione uma foto do produto'); return; }
    const dados = { nome: $('pNome').value.trim(), preco: parseFloat($('pPreco').value), categoria: $('pCat').value, foto };
    if (isEdicao) {
      await updateDoc(doc(db, "produtos", id), dados);
      produtos = produtos.map(p => p.id === id ? { id, ...dados } : p);
    } else {
      const ref = await addDoc(collection(db, "produtos"), dados);
      produtos.push({ id: ref.id, ...dados });
    }
    salvarCache(); resetForm(); renderProdutos(); renderAdminLista(); toast('Produto salvo');
  } catch (err) { console.error(err); toast('Erro ao salvar o produto'); }
  finally { 
    btn.disabled = false; 
    btn.textContent = $('pId').value ? 'Salvar alterações' : 'Cadastrar produto'; 
  }
};

$('lista').addEventListener('click', async e => {
  const ed = e.target.closest('[data-edit]'), del = e.target.closest('[data-del]');
  if (ed) {
    const p = produtos.find(x => x.id === ed.dataset.edit); if (!p) return;
    $('pId').value = p.id; $('pNome').value = p.nome; $('pPreco').value = p.preco;
    $('pCat').value = p.categoria; $('pFotoAtual').value = p.foto || '';
    $('tituloProd').textContent = 'Editando: ' + p.nome;
    $('btnProd').textContent = 'Salvar alterações';
    $('btnCancel').classList.remove('hidden');
    window.scrollTo({ top: $('formProd').offsetTop - 80, behavior: 'smooth' });
  } else if (del) {
    const p = produtos.find(x => x.id === del.dataset.del);
    if (!p || !confirm(`Excluir "${p.nome}"?`)) return;
    try {
      await deleteDoc(doc(db, "produtos", p.id));
      produtos = produtos.filter(x => x.id !== p.id);
      salvarCache(); renderProdutos(); renderAdminLista(); toast('Produto excluído');
    } catch (err) { console.error(err); toast('Erro ao excluir'); }
  }
});

let h2cPromise;
function carregarHtml2canvas() {
  if (window.html2canvas) return Promise.resolve();
  return h2cPromise ||= new Promise((ok, fail) => {
    const s = document.createElement('script');
    s.src = 'https://cdnjs.cloudflare.com/ajax/libs/html2canvas/1.4.1/html2canvas.min.js';
    s.onload = ok; s.onerror = () => { h2cPromise = null; fail(new Error('html2canvas')); };
    document.head.appendChild(s);
  });
}
const imagensProntas = el => Promise.all([...el.querySelectorAll('img')].map(i =>
  i.complete ? Promise.resolve() : new Promise(r => { i.onload = i.onerror = r; })));

$('btnEncarte').onclick = async () => {
  const btn = $('btnEncarte'), original = btn.innerHTML;
  const lista = filtrados();
  if (!lista.length) return toast('Não há produtos na tela para gerar o encarte');
  btn.disabled = true; btn.innerHTML = '⏳ <span>Gerando imagem única...</span>';
  
  try {
    await carregarHtml2canvas();
    const fl = document.createElement('div');
    fl.style.cssText = 'position:absolute;top:-9999px;left:-9999px;width:1080px;background:#0b1f14;padding:50px;font-family:Arial,sans-serif;box-sizing:border-box';
    
    fl.innerHTML = `
      <div style="display:flex;align-items:center;justify-content:space-between;border-bottom:4px solid #d4af37;padding-bottom:25px;margin-bottom:30px">
        <div style="display:flex;align-items:center;gap:24px">
          <img src="${esc(cfg.logo || PLACEHOLDER)}" style="width:110px;height:110px;border-radius:50%;border:4px solid #d4af37;object-fit:cover" crossorigin="anonymous">
          <div>
            <h1 style="color:#d4af37;font-size:52px;font-weight:900;margin:0;line-height:1">PURO TRATO</h1>
            <p style="color:#ccc;font-size:22px;margin:8px 0 0;letter-spacing:3px">RAÇÕES E SUPRIMENTOS</p>
          </div>
        </div>
        <div style="background:#d4af37;color:#000;padding:12px 24px;border-radius:14px;text-align:right">
          <p style="font-size:30px;font-weight:900;margin:0">OFERTAS</p>
        </div>
      </div>
      
      <div style="display:flex;flex-direction:column;gap:16px;margin-bottom:35px">
        ${lista.map(p => `
          <div style="background:#07140d;border:2px solid #d4af3750;border-radius:14px;padding:16px 24px;display:flex;align-items:center;justify-content:space-between">
            <div style="display:flex;align-items:center;gap:22px;min-width:0">
              <img src="${esc(p.foto || PLACEHOLDER)}" style="width:90px;height:90px;border-radius:10px;object-fit:cover;border:2px solid #d4af3766;flex-shrink:0" crossorigin="anonymous">
              <div style="min-width:0">
                <span style="display:inline-block;background:rgba(11,31,20,.9);color:#d4af37;border:1px solid #d4af3780;font-size:13px;font-weight:bold;padding:4px 10px;border-radius:8px;text-transform:uppercase;margin-bottom:6px">${esc(p.categoria)}</span>
                <h3 style="font-size:26px;font-weight:bold;color:#fff;margin:0;white-space:nowrap;overflow:hidden;text-overflow:ellipsis">${esc(p.nome)}</h3>
              </div>
            </div>
            <div style="text-align:right;flex-shrink:0;margin-left:24px">
              <span style="color:#d4af37;font-size:36px;font-weight:900">${brl(p.preco)}</span>
            </div>
          </div>`).join('')}
      </div>

      <div style="text-align:center;background:#07140d;border-radius:18px;padding:22px;border-top:4px solid #d4af37">
        <p style="font-size:24px;color:#ccc;margin:0 0 8px">📍 ${esc(cfg.endereco)}</p>
        <p style="font-size:28px;color:#d4af37;font-weight:bold;margin:0">WhatsApp: ${esc(cfg.whatsapp)}</p>
      </div>`;
    
    fl.querySelectorAll('img').forEach(im => im.addEventListener('error', () => { if (im.src !== PLACEHOLDER) im.src = PLACEHOLDER; }, { once: true }));
    document.body.appendChild(fl);
    
    await imagensProntas(fl);
    const canvas = await html2canvas(fl, { scale: 2.0, useCORS: true, backgroundColor: '#0b1f14' });
    const a = document.createElement('a');
    a.download = 'Ofertas_Puro_Trato.png';
    a.href = canvas.toDataURL('image/png'); 
    a.click();
    fl.remove();
  } catch (err) {
    console.error("Erro ao gerar encarte:", err);
    toast('Não foi possível gerar a imagem. Verifique sua conexão.');
  } finally { 
    btn.innerHTML = original; 
    btn.disabled = false; 
  }
};

renderConfig(); renderCategorias();
if (lerCache()) { renderConfig(); renderCategorias(); renderProdutos(); renderAdminLista(); }
carregarTudo();
</script>
</body>
</html>
