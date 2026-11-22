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
:root{
  --d:#0b1f14;
  --dd:#07140d;
  --g:#d4af37;
  --g-soft:rgba(212,175,55,.28);
  --g-border:rgba(212,175,55,.45);
  --t:#f3f4f6;
  --m:#9ca3af;
  --r:#f87171;
  --b:#60a5fa;
}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{
  margin:0;
  background:var(--d);
  color:var(--t);
  font-family:system-ui,-apple-system,"Segoe UI",Roboto,Arial,sans-serif;
  min-height:100vh;
  display:flex;
  flex-direction:column;
  line-height:1.45;
}
.hidden{display:none!important}
button,input,select{font:inherit}
button{cursor:pointer}
:focus-visible{outline:2px solid var(--g);outline-offset:2px}

header{
  background:var(--dd);
  border-bottom:1px solid var(--g);
  position:sticky;
  top:0;
  z-index:40;
  box-shadow:0 4px 14px rgba(0,0,0,.45);
}
.wrap{max-width:72rem;margin:0 auto;padding:1rem;width:100%}
.row{display:flex;align-items:center;gap:.75rem}
.between{justify-content:space-between}
.flex-1{flex:1}

.logo{
  width:48px;
  height:48px;
  border-radius:50%;
  border:2px solid var(--g);
  object-fit:cover;
  background:var(--d);
  flex-shrink:0;
}
h1{margin:0;font-size:1.5rem;font-weight:900;color:var(--g);letter-spacing:.03em;line-height:1.1}
.sub{margin:.15rem 0 0;font-size:.7rem;color:var(--m);letter-spacing:.1em}

.btn{
  background:var(--g);
  color:#090d0a;
  font-weight:700;
  border:0;
  border-radius:.5rem;
  padding:.6rem 1rem;
  font-size:.85rem;
  white-space:nowrap;
  transition:transform .12s ease,opacity .15s ease,background-color .15s ease,color .15s ease;
}
.btn:hover:not(:disabled){opacity:.92;transform:translateY(-1px)}
.btn:active:not(:disabled){transform:translateY(0)}
.btn:disabled{opacity:.5;cursor:wait}
.btn.o{background:var(--d);color:var(--g);border:1px solid var(--g)}
.btn.o:hover:not(:disabled){background:var(--g);color:#090d0a}
.btn.r{background:rgba(220,38,38,.2);color:var(--r);border:1px solid rgba(239,68,68,.35);font-size:.75rem;padding:.35rem .75rem}
.btn.r:hover:not(:disabled){background:#dc2626;color:#fff}
.btn.b{background:rgba(37,99,235,.22);color:var(--b);border:1px solid rgba(59,130,246,.38);font-size:.75rem;padding:.35rem .75rem}
.btn.b:hover:not(:disabled){background:#2563eb;color:#fff}
.btn.link{background:none;color:var(--m);text-decoration:underline;padding:.25rem .5rem;font-size:.8rem}
.btn.link:hover:not(:disabled){color:var(--t)}

.box{
  background:var(--dd);
  border:1px solid var(--g-border);
  border-radius:.75rem;
  padding:1.25rem;
  margin-bottom:1.5rem;
  box-shadow:0 10px 25px rgba(0,0,0,.35);
}
.box h2,.box h3{color:var(--g);margin:0 0 .75rem}
.small{font-size:.8rem;color:#d1d5db;margin:.25rem 0}
.tag{
  border:1px solid var(--g);
  color:var(--g);
  background:var(--g-soft);
  padding:.5rem 1rem;
  border-radius:.5rem;
  font-size:.75rem;
  font-weight:700;
}

.inp{
  width:100%;
  background:var(--d);
  border:1px solid rgba(212,175,55,.42);
  border-radius:.5rem;
  padding:.65rem .75rem;
  color:#fff;
  font-size:.875rem;
  transition:border-color .15s ease;
}
.inp:focus{outline:none;border-color:var(--g);box-shadow:0 0 0 2px rgba(212,175,55,.22)}
label{display:block;font-size:.75rem;color:#d1d5db;margin-bottom:.3rem}

.g2{display:grid;grid-template-columns:1fr;gap:1rem;margin-bottom:1rem}
@media(min-width:640px){.g2{grid-template-columns:1fr 1fr}}

.bar{display:flex;flex-direction:column;gap:1rem;margin-bottom:1.5rem}
@media(min-width:640px){.bar{flex-direction:row;justify-content:space-between;align-items:center}}

.cats{display:flex;gap:.5rem;overflow-x:auto;padding-bottom:.4rem;scrollbar-width:none}
.cats::-webkit-scrollbar{display:none}
.cat{
  background:var(--dd);
  border:1px solid rgba(212,175,55,.5);
  color:#d1d5db;
  padding:.42rem .9rem;
  border-radius:.5rem;
  font-size:.75rem;
  font-weight:700;
  white-space:nowrap;
  transition:background-color .15s ease,color .15s ease,border-color .15s ease;
}
.cat:hover{border-color:var(--g);color:#fff}
.cat.on{background:var(--g);color:#090d0a;border-color:var(--g)}

#grid{display:grid;grid-template-columns:repeat(3,1fr);gap:.5rem}
@media(min-width:640px){#grid{gap:1.5rem}}
@media(min-width:768px){#grid{grid-template-columns:repeat(4,1fr)}}
@media(min-width:1024px){#grid{grid-template-columns:repeat(5,1fr)}}

.full{grid-column:1/-1;text-align:center;padding:3rem 0;color:var(--m)}

.p{
  background:var(--dd);
  border:1px solid var(--g-border);
  border-radius:.5rem;
  overflow:hidden;
  display:flex;
  flex-direction:column;
  justify-content:space-between;
  content-visibility:auto;
  contain-intrinsic-size:200px 180px;
  transition:border-color .15s ease,transform .15s ease;
}
.p:hover{border-color:var(--g);transform:translateY(-2px)}
.p .im{height:80px;background:#111c15;position:relative;overflow:hidden}
.p img{width:100%;height:100%;object-fit:cover;display:block}
.p .cat-tag{
  display:none;
  position:absolute;
  top:8px;
  right:8px;
  background:rgba(11,31,20,.88);
  border:1px solid var(--g);
  color:var(--g);
  font-size:10px;
  font-weight:700;
  padding:3px 10px;
  border-radius:99px;
  text-transform:uppercase;
  max-width:80%;
  overflow:hidden;
  text-overflow:ellipsis;
  white-space:nowrap;
}
.p h3{
  margin:0;
  padding:.5rem .5rem .25rem;
  font-size:10px;
  line-height:1.25;
  display:-webkit-box;
  -webkit-line-clamp:2;
  -webkit-box-orient:vertical;
  overflow:hidden;
}
.p .pr{padding:0 .5rem .5rem;color:var(--g);font-weight:900;font-size:.75rem}

@media(min-width:640px){
  .p .im{height:128px}
  .p .cat-tag{display:block}
  .p h3{font-size:.875rem;padding:1rem 1rem .25rem}
  .p .pr{padding:0 1rem 1rem;font-size:1rem}
}
@media(min-width:768px){
  .p .im{height:192px}
  .p h3{font-size:1rem}
  .p .pr{font-size:1.125rem}
}

.spin{
  display:inline-block;
  width:24px;
  height:24px;
  border:3px solid rgba(212,175,55,.28);
  border-top-color:var(--g);
  border-radius:50%;
  animation:s .8s linear infinite;
}
@keyframes s{to{transform:rotate(360deg)}}
@media(prefers-reduced-motion:reduce){
  html{scroll-behavior:auto}
  .spin{animation-duration:2s}
  .btn,.p,.cat,.inp{transition:none}
}

footer{
  background:var(--dd);
  border-top:1px solid var(--g-border);
  margin-top:3rem;
  padding:1.5rem 1rem;
  text-align:center;
  font-size:.75rem;
  color:var(--m);
}
footer p{margin:.25rem 0}

.modal{
  position:fixed;
  inset:0;
  background:rgba(0,0,0,.78);
  z-index:60;
  display:flex;
  align-items:center;
  justify-content:center;
  padding:1rem;
}
.modal .box{max-width:24rem;width:100%;margin:0;position:relative;background:var(--d);border-color:var(--g)}
.x{position:absolute;top:.75rem;right:1rem;background:none;border:0;color:var(--m);font-size:1.25rem;line-height:1}
.x:hover{color:#fff}

.item{
  background:var(--d);
  border:1px solid var(--g-border);
  padding:.75rem;
  border-radius:.5rem;
  display:flex;
  justify-content:space-between;
  align-items:center;
  gap:.5rem;
  font-size:.875rem;
}
.item .info{display:flex;align-items:center;gap:.75rem;min-width:0}
.item img{width:40px;height:40px;object-fit:cover;border-radius:.375rem;border:1px solid rgba(212,175,55,.4);flex-shrink:0}
.item .txt{min-width:0}
.item b,.item small{display:block;overflow:hidden;text-overflow:ellipsis;white-space:nowrap}
.item small{color:var(--g);font-size:.75rem;font-weight:600}

.chips{display:flex;flex-wrap:wrap;gap:.5rem}
.chip{
  background:var(--d);
  border:1px solid var(--g-border);
  padding:.35rem .75rem;
  border-radius:.5rem;
  display:flex;
  align-items:center;
  gap:.5rem;
  font-size:.75rem;
  font-weight:600;
}
.chip button{background:none;border:0;color:var(--r);padding:0;line-height:1}
.chip button:hover{color:#fff}

#lista{display:grid;gap:.5rem;max-height:24rem;overflow-y:auto;padding-right:.25rem}

.toast{
  position:fixed;
  bottom:1rem;
  left:50%;
  transform:translateX(-50%);
  background:var(--g);
  color:#090d0a;
  font-weight:700;
  padding:.6rem 1.2rem;
  border-radius:.5rem;
  z-index:80;
  font-size:.85rem;
  box-shadow:0 6px 20px rgba(0,0,0,.5);
  max-width:calc(100vw - 2rem);
  text-align:center;
}
</style>
</head>
<body>

<header>
  <div class="wrap row between" style="flex-wrap:wrap">
    <div class="row">
      <img class="logo" id="logoTopo" alt="Logo Puro Trato" width="48" height="48">
      <div>
        <h1>PURO TRATO</h1>
        <p class="sub">RAÇÕES E SUPRIMENTOS</p>
      </div>
    </div>
    <button id="btnTopo" class="btn o" type="button">🔒 Área Restrita</button>
  </div>
</header>

<main id="vitrine" class="wrap flex-1" style="padding-top:2rem">
  <div class="box row between" style="flex-wrap:wrap;gap:1rem">
    <div>
      <h2 style="font-size:1.25rem">🏪 Bem-vindo à nossa Vitrine</h2>
      <p class="small" id="infoEnd"></p>
      <p class="small" id="infoWhats"></p>
    </div>
    <span class="tag">ℹ️ Vendas na Loja Física</span>
  </div>

  <div class="bar">
    <div class="row" style="gap:.5rem;flex-wrap:wrap">
      <input id="busca" class="inp" type="search" placeholder="🔍 Pesquisar produto..." style="min-width:12rem;max-width:18rem;border-color:rgba(212,175,55,.55)" autocomplete="off" aria-label="Pesquisar produto">
      <button id="btnEncarte" class="btn" type="button">🖼️ <span>Gerar Encarte</span></button>
    </div>
    <div id="filtros" class="cats" role="tablist" aria-label="Categorias de produtos"></div>
  </div>

  <div id="grid"><div class="full"><span class="spin"></span><p>Carregando produtos...</p></div></div>
</main>

<main id="admin" class="wrap hidden flex-1" style="max-width:56rem;padding-top:2rem">
  <div class="row between" style="border-bottom:1px solid var(--g-border);padding-bottom:1rem;margin-bottom:1.5rem">
    <h2 style="color:var(--g);margin:0;font-size
