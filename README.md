<!DOCTYPE html>
<html lang="bn">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>শ্রী শ্রী জগন্নাথ–বলদেব–সুভদ্রা মন্দির — দান তহবিল</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Baloo+Da+2:wght@500;600;700;800&family=Hind+Siliguri:wght@400;500;600;700&family=Noto+Serif+Bengali:wght@600;700;800&display=swap" rel="stylesheet">
<style>
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body { font-family: "Hind Siliguri", system-ui, sans-serif; background: #e8f5ea; color: #17351f; }
  .display { font-family: "Baloo Da 2", "Noto Serif Bengali", Georgia, sans-serif; letter-spacing: .01em; }
  header.hero { position: relative; }
  header.hero img { width: 100%; height: 300px; object-fit: cover; display: block; }
  header.hero .overlay { position: absolute; inset: auto 0 0 0; padding: 48px 16px 16px; text-align: center;
    background: linear-gradient(to top, rgba(0,0,0,.78), rgba(0,0,0,.3), transparent); color: #fff; }
  header.hero h1 { font-size: 30px; }
  header.hero p { color: #fde68a; margin-top: 4px; }
  .marquee { overflow: hidden; background: #14532d; color: #ffe9c9; padding: 8px 0; }
  .marquee-track { display: inline-flex; white-space: nowrap; animation: mq 30s linear infinite; font-weight: 600; }
  @keyframes mq { from { transform: translateX(0); } to { transform: translateX(-50%); } }
  main { max-width: 880px; margin: 0 auto; padding: 20px 16px 48px; }
  .card { background: #fdfffc; border: 1px solid #b7dec0; border-radius: 16px; padding: 18px; margin-bottom: 18px;
    box-shadow: 0 1px 3px rgba(23,53,31,.06); }
  .card.gold { border: 2px solid #e8930c; }
  label { display: block; font-size: 14px; font-weight: 500; margin-bottom: 10px; }
  label span { display: block; margin-bottom: 4px; }
  input, select, textarea { width: 100%; border: 1px solid #b7dec0; border-radius: 10px; padding: 9px 12px;
    font: inherit; background: #fdfffc; color: #17351f; }
  button { font: inherit; cursor: pointer; border: none; border-radius: 10px; padding: 10px 18px; font-weight: 600;
    background: #14632e; color: #fff; }
  button.ghost { background: #fdfffc; color: #17351f; border: 1px solid #b7dec0; font-weight: 500; }
  button.green { background: #15803d; }
  button.red { background: #b91c1c; }
  button:disabled { opacity: .5; }
  .tabs { display: grid; grid-template-columns: 1fr 1fr; gap: 8px; margin-bottom: 16px; }
  .tabs button { background: #d9eeda; color: #17351f; }
  .tabs button.on { background: #14632e; color: #fff; }
  .err { background: #fef2f2; color: #b91c1c; border-radius: 10px; padding: 8px 12px; font-size: 14px; margin-bottom: 10px; }
  .ok { background: #f0fdf4; color: #15803d; border-radius: 10px; padding: 8px 12px; font-size: 14px; margin-bottom: 10px; }
  .dim { color: #55755e; font-size: 14px; }
  .grid2 { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; }
  .grid4 { display: grid; grid-template-columns: repeat(4, 1fr); gap: 10px; }
  @media (max-width: 640px) { .grid4 { grid-template-columns: 1fr 1fr; } }
  .stat { background: #d9eeda; border-radius: 12px; padding: 12px; }
  .stat p:first-child { font-size: 12px; color: #55755e; }
  .stat p:last-child { font-family: "Noto Serif Bengali", serif; font-size: 22px; font-weight: 700; }
  .bar { height: 14px; background: #d9eeda; border-radius: 999px; overflow: hidden; }
  .bar > div { height: 100%; background: linear-gradient(to right, #e8930c, #c9920e); border-radius: 999px; }
  .badge { display: inline-block; border-radius: 999px; padding: 2px 10px; font-size: 12px; font-weight: 600; }
  .badge.pending { background: #fef3c7; color: #92400e; }
  .badge.confirmed { background: #dcfce7; color: #166534; }
  .badge.rejected { background: #fee2e2; color: #991b1b; }
  .badge.role { background: #d9eeda; color: #17351f; }
  .badge.main { background: #14632e; color: #fff; }
  ul.rows { list-style: none; }
  ul.rows li { border-bottom: 1px solid #b7dec0; padding: 10px 0; display: flex; justify-content: space-between; gap: 12px; }
  ul.rows li:last-child { border-bottom: none; }
  .methods { display: grid; grid-template-columns: repeat(3, 1fr); gap: 8px; margin-bottom: 12px; }
  @media (max-width: 640px) { .methods { grid-template-columns: 1fr 1fr; } }
  .methods button { background: #fdfffc; color: #17351f; border: 1px solid #b7dec0; text-align: left; font-weight: 500; }
  .methods button.on { border: 2px solid #14632e; background: #dcf2e1; font-weight: 600; }
  .acct { background: #d9eeda; border-radius: 12px; padding: 12px; margin-bottom: 12px; }
  .acct .num { font-family: "Noto Serif Bengali", serif; font-size: 22px; font-weight: 700; }
  .topbar { position: sticky; top: 0; z-index: 40; background: rgba(253,255,252,.96); border-bottom: 1px solid #b7dec0;
    padding: 10px 16px; display: flex; flex-wrap: wrap; gap: 8px; align-items: center; }
  .topbar .brand { font-family: "Noto Serif Bengali", serif; font-weight: 700; margin-right: auto; }
  .pill { border-radius: 999px; padding: 6px 14px; font-size: 14px; }
  .pill.on { background: #14632e; color: #fff; }
  .pill.off { background: #fdfffc; border: 1px solid #b7dec0; color: #17351f; }
  .admintabs { display: flex; gap: 8px; overflow-x: auto; margin-bottom: 16px; }
  #splash { position: fixed; inset: 0; z-index: 50; background: #0d3b1e; color: #fff; display: flex;
    flex-direction: column; align-items: center; justify-content: center; text-align: center; padding: 24px; cursor: pointer; }
  #splash img { width: 168px; height: 168px; border-radius: 50%; object-fit: cover; border: 4px solid #c9920e;
    animation: rise .7s ease-out both; }
  #splash .jai { font-family: "Noto Serif Bengali", serif; font-size: 64px; font-weight: 800; line-height: 1.2;
    background: linear-gradient(to right, #fde68a, #facc15, #fde68a); -webkit-background-clip: text; background-clip: text;
    color: transparent; animation: jai 1.1s ease-out .25s both; }
  @keyframes rise { from { opacity: 0; transform: translateY(18px); } to { opacity: 1; transform: none; } }
  @keyframes jai { 0% { opacity: 0; transform: scale(.82); } 55% { opacity: 1; transform: scale(1.06); } 100% { opacity: 1; transform: scale(1); } }
  .hidden { display: none !important; }
</style>
</head>
<body>
<div id="app"></div>
<div id="splash" class="hidden"></div>

<script>
"use strict";
/* শ্রী শ্রী জগন্নাথ–বলদেব–সুভদ্রা মন্দির — দান তহবিল (standalone সংস্করণ)
   সব তথ্য এই ব্রাউজারের localStorage-এ সংরক্ষিত থাকে। */
var DB_KEY = "jagannath_donation_db_v1";
var MAX_ADMINS = 4;
var METHODS = [
  { key: "bkash", label: "বিকাশ" },
  { key: "nagad", label: "নগদ" },
  { key: "rocket", label: "রকেট" },
  { key: "bank", label: "ব্যাংক ট্রান্সফার" },
  { key: "cash", label: "নগদ ক্যাশ" }
];
var BN = ["০","১","২","৩","৪","৫","৬","৭","৮","৯"];
function bn(n) { return String(n).replace(/\d/g, function (d) { return BN[Number(d)]; }); }
function normalizePhoneDigits(raw) {
  var map = { "০": "0", "১": "1", "২": "2", "৩": "3", "৪": "4", "৫": "5", "৬": "6", "৭": "7", "৮": "8", "৯": "9" };
  return String(raw == null ? "" : raw).trim().replace(/[০-৯]/g, function (d) { return map[d] || d; }).replace(/[\s-]/g, "");
}
var MOBILE_11_DIGIT_MESSAGE = "মোবাইল নম্বর অবশ্যই ১১ ডিজিটের হতে হবে — ১১ ডিজিটের কম হলে অ্যাকাউন্ট তৈরি করা যাবে না। সঠিক ১১ ডিজিটের মোবাইল নম্বর লিখুন (যেমন: ০১৭XXXXXXXX)।";
function mobileNumberError(raw) {
  return /^\d{11}$/.test(normalizePhoneDigits(raw)) ? "" : MOBILE_11_DIGIT_MESSAGE;
}
function tk(n) {
  var s = Number(n).toLocaleString("en-IN");
  return "৳" + bn(s);
}
function ordinal(n) {
  var suf = n === 1 ? "ম" : (n === 2 || n === 3) ? "য়" : n === 4 ? "র্থ" : n === 6 ? "ষ্ঠ" : "ম";
  return bn(n) + suf + " কিস্তি";
}
function fmtDate(ts) {
  return new Intl.DateTimeFormat("bn-BD", { day: "numeric", month: "long", year: "numeric" }).format(new Date(ts));
}
function esc(s) {
  return String(s == null ? "" : s).replace(/[&<>"']/g, function (c) {
    return { "&": "&amp;", "<": "&lt;", ">": "&gt;", '"': "&quot;", "'": "&#39;" }[c];
  });
}
function fmtDateTime(ts) {
  return new Intl.DateTimeFormat("bn-BD", { day: "numeric", month: "long", year: "numeric", hour: "numeric", minute: "2-digit" }).format(new Date(ts));
}
function deviceInfo() { try { return (navigator.userAgent || "").slice(0, 300); } catch (e) { return ""; } }
function logReset(acc, event, detail) {
  db.resetLog.unshift({ id: db.nextId++, name: acc ? acc.name : "", phone: acc ? acc.phone : "",
    role: acc ? acc.role : "", event: event, detail: detail || "", device: deviceInfo(), at: Date.now() });
  if (db.resetLog.length > 200) db.resetLog.length = 200;
}
function resetLocked(acc) { return !!(acc.lockUntil && acc.lockUntil > Date.now()); }
var RESET_LOCK_MSG = "পরপর ৩ বার ভুল কোড দেওয়ায় এই অ্যাকাউন্টটি ৩০ মিনিটের জন্য লক হয়ে গেছে — এই সময়ে লগইন বা রিসেট কোনোটাই করা যাবে না। ৩০ মিনিট পর আবার চেষ্টা করুন, অথবা মূল অ্যাডমিনের সঙ্গে যোগাযোগ করুন।";
function wrongCode(acc, r) {
  r.attempts = (r.attempts || 0) + 1;
  if (r.attempts >= 3) {
    delete db.resets[acc.phone];
    acc.lockUntil = Date.now() + 30 * 60 * 1000;
    logReset(acc, "ভুল কোডে অ্যাকাউন্ট লক", "পরপর ৩ বার ভুল কোড — অ্যাকাউন্ট ৩০ মিনিটের জন্য লক (লগইনসহ)।");
    save();
    return RESET_LOCK_MSG;
  }
  logReset(acc, "ভুল কোড দেওয়া হয়েছে", r.attempts + " বার ভুল — আর " + (3 - r.attempts) + " বার ভুল দিলে লক হয়ে যাবে।");
  save();
  return "কোডটি মিলছে না — আর " + bn(3 - r.attempts) + " বার চেষ্টা করা যাবে, তারপর অ্যাকাউন্ট ৩০ মিনিটের জন্য লক হয়ে যাবে।";
}
function load() {
  try { return JSON.parse(localStorage.getItem(DB_KEY)); } catch (e) { return null; }
}
function freshDb() {
  return {
    accounts: [], payments: [], pledges: {}, sessionId: null, nextId: 1, resets: {},
    emailVerifs: {}, requests: [], resetLog: [], recovery: { email: "", question: "", answer: "" },
    settings: { bkash: "০১৭XXXXXXXX", nagad: "০১৭XXXXXXXX", rocket: "০১৭XXXXXXXX", bank: "অ্যাকাউন্ট নম্বর: ০১৭XXXXXXXXXX" }
  };
}
var db = load() || freshDb();
if (!db.resets) db.resets = {};
if (!db.emailVerifs) db.emailVerifs = {};
if (!db.requests) db.requests = [];
if (!db.resetLog) db.resetLog = [];
if (!db.recovery) db.recovery = { email: "", question: "", answer: "" };
function emailValid(v) { return /^[^\s@]+@[^\s@]+\.[^\s@]+$/.test(String(v || "").trim()); }
function issueEmailCode(phone, purpose) {
  var code = String(Math.floor(100000 + Math.random() * 900000));
  db.emailVerifs[phone + "|" + purpose] = { code: code, exp: Date.now() + 10 * 60 * 1000, attempts: 0 };
  return code;
}
function checkEmailCode(phone, purpose, entered) {
  var key = phone + "|" + purpose;
  var r = db.emailVerifs[key];
  if (!r) return "কোনো সক্রিয় যাচাই কোড নেই — আগে কোডের অনুরোধ করুন।";
  if (r.exp < Date.now()) { delete db.emailVerifs[key]; return "কোডটির মেয়াদ শেষ হয়ে গেছে (১০ মিনিট) — নতুন কোডের অনুরোধ করুন।"; }
  if (r.code !== normalizePhoneDigits(entered)) {
    r.attempts = (r.attempts || 0) + 1;
    if (r.attempts >= 5) { delete db.emailVerifs[key]; return "পরপর ৫ বার ভুল কোড দেওয়ায় এই কোডটি বাতিল হয়ে গেছে — নতুন কোডের অনুরোধ করুন।"; }
    return "কোডটি মিলছে না — আর " + bn(5 - r.attempts) + " বার চেষ্টা করা যাবে।";
  }
  delete db.emailVerifs[key];
  return "";
}
function emailServiceNotice() {
  return '<p style="border:2px dashed #e8930c;background:#fffbeb;color:#92400e;border-radius:10px;padding:8px 12px;font-size:14px;margin-bottom:12px"><strong>গুরুত্বপূর্ণ:</strong> এই অ্যাপে এখনো কোনো ইমেইল সার্ভিস যুক্ত হয়নি, তাই যাচাই কোডটি আসলে ইমেইলে পাঠানো যাচ্ছে না — আর নিরাপত্তার জন্য কোডটি অ্যাপের ভেতরে কোথাও দেখানোও হয় না। ইমেইল সার্ভিস যুক্ত হলেই কোড শুধু সংশ্লিষ্ট ইমেইলেই যাবে এবং এই ধাপটি সম্পূর্ণ করা যাবে।</p>';
}
function save() { localStorage.setItem(DB_KEY, JSON.stringify(db)); }
function me() {
  for (var i = 0; i < db.accounts.length; i++) if (db.accounts[i].id === db.sessionId) return db.accounts[i];
  return null;
}
function totalsFor(donorId) {
  var pledge = db.pledges[donorId] || null;
  var paid = 0, pending = 0;
  db.payments.forEach(function (p) {
    if (p.donorId !== donorId) return;
    if (p.status === "confirmed") paid += p.amount;
    if (p.status === "pending") pending += p.amount;
  });
  var pledged = pledge ? pledge.amount : 0;
  return { pledge: pledge, pledged: pledged, paid: paid, pending: pending, remaining: Math.max(0, pledged - paid) };
}
function nextNo(donorId) {
  var m = 0;
  db.payments.forEach(function (p) { if (p.donorId === donorId && p.no > m) m = p.no; });
  return m + 1;
}
function methodLabel(k) {
  for (var i = 0; i < METHODS.length; i++) if (METHODS[i].key === k) return METHODS[i].label;
  return k;
}
function badge(status) {
  if (status === "confirmed") return '<span class="badge confirmed">নিশ্চিত হয়েছে</span>';
  if (status === "rejected") return '<span class="badge rejected">বাতিল হয়েছে</span>';
  return '<span class="badge pending">যাচাই বাকি</span>';
}
function progress(paid, pledged) {
  var pct = pledged > 0 ? Math.min(100, Math.round(paid / pledged * 100)) : 0;
  return '<div class="bar"><div style="width:' + pct + '%"></div></div>' +
    '<p class="dim" style="text-align:right;margin-top:4px">' + bn(pct) + '% পূরণ হয়েছে</p>';
}
function paymentRow(p, donorName, mine) {
  var canEdit = mine && (p.status === "pending" || p.status === "rejected");
  var h = '<li><div>' +
    (donorName ? '<div style="font-weight:600">' + esc(donorName) + "</div>" : "") +
    "<div>" + ordinal(p.no) + " • " + methodLabel(p.method) + "</div>" +
    '<div class="dim">' + fmtDate(p.date) + "</div>" +
    (p.trx ? '<div class="dim">লেনদেন নম্বর: ' + esc(p.trx) + "</div>" : "") +
    (p.sender ? '<div class="dim">প্রেরক: ' + esc(p.sender) + "</div>" : "") +
    (p.edits ? '<div class="dim">সংশোধন করে আবার পাঠানো হয়েছে' + (p.editedAt ? " (" + fmtDate(p.editedAt) + ")" : "") + "</div>" : "") +
    (canEdit && p.status === "rejected" ? '<div style="color:#b91c1c;font-size:14px;margin-top:4px">এই কিস্তিটি বাতিল হয়েছে — তথ্যে ভুল থাকলে ঠিক করে আবার পাঠান।</div>' : "") +
    '</div><div style="text-align:right"><div class="display" style="font-size:18px;font-weight:700">' +
    tk(p.amount) + "</div>" + badge(p.status);
  if (canEdit) {
    h += '<div style="margin-top:6px"><button type="button" class="ghost" style="padding:5px 10px;font-size:13px;color:#14632e" onclick="toggleEditPay(' + p.id + ')">' +
      (ui.editPay === p.id ? "বন্ধ করুন" : "তথ্য সংশোধন করুন") + "</button></div>";
  }
  h += "</div></li>";
  if (canEdit && ui.editPay === p.id) {
    h += '<li style="display:block">' + editPayFormHtml(p) + "</li>";
  }
  return h;
}
function editPayFormHtml(p) {
  var h = '<form onsubmit="return doEditPay(event,' + p.id + ')" style="background:#d9eeda;border-radius:12px;padding:12px">' +
    '<p style="font-weight:600;margin-bottom:6px">' + ordinal(p.no) + " — তথ্য সংশোধন করে আবার পাঠান</p>" +
    '<p class="dim" style="margin-bottom:10px">ভুল তথ্য ঠিক করে পাঠালে কিস্তিটি আবার যাচাই বাকি অবস্থায় যাবে — অ্যাডমিন নতুন তথ্য মিলিয়ে যাচাই করবেন।</p>' +
    '<div class="grid2">' +
    '<label><span>পরিমাণ (টাকা)</span><input id="ep-amount" type="number" min="1" required value="' + p.amount + '"></label>' +
    '<label><span>মাধ্যম</span><select id="ep-method">' +
    METHODS.map(function (m) { return '<option value="' + m.key + '"' + (m.key === p.method ? " selected" : "") + ">" + m.label + "</option>"; }).join("") +
    "</select></label>" +
    '<label><span>লেনদেন নম্বর (ট্রান্সঅ্যাকশন আইডি)</span><input id="ep-trx" value="' + esc(p.trx || "") + '"></label>' +
    '<label><span>যে নম্বর থেকে পাঠিয়েছেন</span><input id="ep-sender" inputmode="tel" value="' + esc(p.sender || "") + '"></label></div>' +
    '<div style="display:flex;gap:8px;flex-wrap:wrap"><button type="submit">সংশোধন করে আবার পাঠান</button>' +
    '<button type="button" class="ghost" onclick="toggleEditPay(' + p.id + ')">বাতিল</button></div></form>';
  return h;
}
function toggleEditPay(id) { ui.editPay = ui.editPay === id ? null : id; ui.err = ""; render(); }
function doEditPay(e, id) {
  e.preventDefault();
  var u = me();
  var p = null;
  db.payments.forEach(function (x) { if (x.id === id) p = x; });
  if (!p || p.donorId !== u.id || p.status === "confirmed") { ui.err = "এই কিস্তিটি এখন বদলানো যাবে না।"; render(); return false; }
  var amount = Math.round(Number(document.getElementById("ep-amount").value));
  var method = document.getElementById("ep-method").value;
  var trx = document.getElementById("ep-trx").value.trim();
  var sender = document.getElementById("ep-sender").value.trim();
  if (!amount || amount <= 0) { ui.err = "সঠিক টাকার পরিমাণ লিখুন।"; render(); return false; }
  if (method !== "cash" && !trx) { ui.err = "লেনদেন নম্বর (ট্রান্সঅ্যাকশন আইডি) লিখুন — অ্যাডমিন এটি মিলিয়ে যাচাই করবেন।"; render(); return false; }
  p.amount = amount; p.method = method; p.trx = trx; p.sender = sender;
  p.status = "pending"; p.edits = (p.edits || 0) + 1; p.editedAt = Date.now();
  ui.editPay = null;
  save(); ui.err = ""; ui.ok = "সংশোধন পাঠানো হয়েছে — অ্যাডমিন আবার যাচাই করবেন।"; render();
  return false;
}

/* ------------------------------ অবস্থা (state) ------------------------------ */
var ui = { authTab: "login", view: "mine", adminTab: "overview", payMethod: "bkash",
           expandedDonor: null, search: "", err: "", ok: "", confirmRemove: null,
           editPay: null, forgot: false, resetPhone: "", resetPwFor: null,
           adminReset: false, setupStep: 1, setupPending: null,
           recovery: false, recMode: "email", recStep: 1, recPhone: "",
           recEmailStep: 1, recEmail: "", approveFor: null, emailFor: null };

function showSplash(name) {
  var s = document.getElementById("splash");
  s.innerHTML = '<img src="assets/deities.jpg" alt="শ্রী শ্রী জগন্নাথ, বলদেব ও সুভদ্রা মহারানীর বিগ্রহ">' +
    '<p style="margin-top:22px;font-size:18px;color:#fde68a">স্বাগতম, ' + esc(name) + "</p>" +
    '<p class="jai">জয় জগন্নাথ</p>' +
    '<p style="margin-top:14px;color:#fef3c7">প্রভুর সেবায় আপনার প্রতিটি দানই আশীর্বাদ হয়ে ফিরে আসুক।</p>' +
    '<p style="margin-top:28px;font-size:14px;color:rgba(254,243,199,.6)">এগিয়ে যেতে চাপ দিন</p>';
  s.classList.remove("hidden");
  s.onclick = function () { s.classList.add("hidden"); };
  setTimeout(function () { s.classList.add("hidden"); }, 3400);
}

/* --------------------------------- auth --------------------------------- */
function renderAuth() {
  var hasAdmin = db.accounts.some(function (a) { return a.role === "admin"; });
  var slogan = "॥ জয় জগন্নাথ ॥ আপনার ভালোবাসার দানেই গড়ে উঠবে প্রভুর মন্দির — প্রতিটি দান পৌঁছাক সেবায়, প্রতিটি টাকা হোক আশীর্বাদ ॥ হরে কৃষ্ণ ॥ ";
  var half = "<span>" + slogan + slogan + slogan + "</span>";
  var html = '<header class="hero"><img src="assets/deities.jpg" alt="শ্রী শ্রী জগন্নাথ, বলদেব ও সুভদ্রা মহারানীর বিগ্রহ">' +
    '<div class="overlay"><h1 class="display">শ্রী শ্রী জগন্নাথ–বলদেব–সুভদ্রা মন্দির</h1>' +
    "<p>মন্দির উন্নয়ন তহবিল — দান ও চাঁদা সংগ্রহ</p>" +
    '<p style="font-weight:600;color:#fff7ed">ঠিকানা: মেহারন, মতলব দক্ষিণ, চাঁদপুর</p></div></header>' +
    '<div class="marquee"><div class="marquee-track">' + half + half + "</div></div><main>";
  if (!hasAdmin) {
    html += '<section class="card gold"><h2 class="display" style="font-size:20px">প্রথমবার সেটআপ — মূল অ্যাডমিন অ্যাকাউন্ট</h2>' +
      '<p class="dim" style="margin:6px 0 12px">এই অ্যাপে এখনো কোনো অ্যাডমিন নেই। মন্দিরের পরিচালক (মূল অ্যাডমিন) নিজের অ্যাকাউন্ট তৈরি করুন — তিনিই পরে আরও সর্বোচ্চ ৩ জন অ্যাডমিন যোগ করতে পারবেন। মূল অ্যাডমিনের অ্যাকাউন্টে মোবাইল নম্বরের পাশাপাশি একটি ইমেইল ঠিকানাও লাগবে — ইমেইলে যাচাই কোড যাবে, কোড মিললেই কেবল অ্যাকাউন্ট তৈরি হবে। পরে পাসওয়ার্ড ভুলে গেলেও এই ইমেইল যাচাই দিয়েই রিসেট করা যাবে।</p>';
    if (ui.setupStep === 1) {
      html += '<form onsubmit="return doSetup(event)">' +
        '<label><span>আপনার নাম</span><input id="su-name" required placeholder="পুরো নাম লিখুন"></label>' +
        '<label><span>মোবাইল নম্বর (লগইন আইডি)</span><input id="su-phone" required placeholder="০১৭XXXXXXXX" inputmode="tel" maxlength="11"><small class="dim">মোবাইল নম্বর অবশ্যই ১১ ডিজিটের হতে হবে — কম হলে অ্যাকাউন্ট তৈরি হবে না।</small></label>' +
        '<label><span>ইমেইল ঠিকানা</span><input id="su-email" type="email" required placeholder="যেমন: you@example.com"><small class="dim">এই ইমেইলে যাচাই কোড যাবে — কোড বসালেই অ্যাকাউন্ট তৈরি হবে। পাসওয়ার্ড ভুলে গেলে রিসেটও এই ইমেইল দিয়েই হবে।</small></label>' +
        '<label><span>পাসওয়ার্ড</span><input id="su-pass" type="password" required minlength="4" placeholder="কমপক্ষে ৪ অক্ষর"></label>' +
        '<label><span>ঠিকানা (ঐচ্ছিক)</span><input id="su-addr" placeholder="গ্রাম / এলাকা, উপজেলা, জেলা"></label>' +
        '<button type="submit" style="width:100%">ইমেইলে যাচাই কোড পাঠান</button></form>';
    } else {
      html += '<p class="ok">যাচাই কোড তৈরি হয়েছে এই ইমেইলের জন্য: <strong>' + esc(ui.setupPending ? ui.setupPending.email : "") + '</strong> — কোডটি বসালেই মূল অ্যাডমিন অ্যাকাউন্ট তৈরি হয়ে যাবে। কোডের মেয়াদ ১০ মিনিট, এবং কোডটি অ্যাপের ভেতরে কোথাও দেখানো হয় না।</p>' +
        emailServiceNotice() +
        '<form onsubmit="return doSetupVerify(event)">' +
        '<label><span>ইমেইলে আসা যাচাই কোড</span><input id="su-code" required placeholder="৬ সংখ্যার কোড" inputmode="numeric"></label>' +
        '<button type="submit" style="width:100%">কোড যাচাই করে অ্যাকাউন্ট তৈরি করুন</button></form>' +
        '<p style="text-align:center;margin-top:10px"><a href="#" onclick="ui.setupStep=1;ui.err=\'\';render();return false" style="color:#14632e;font-weight:600">তথ্য বদলে আবার কোড পাঠান</a></p>';
    }
    html += "</section>";
  }
  html += '<section class="card"><div class="tabs">' +
    '<button type="button" class="' + (ui.authTab === "login" ? "on" : "") + '" onclick="setAuthTab(\'login\')">লগইন</button>' +
    '<button type="button" class="' + (ui.authTab === "register" ? "on" : "") + '" onclick="setAuthTab(\'register\')">নতুন দাতা অ্যাকাউন্ট</button></div>';
  if (ui.err) html += '<p class="err">' + esc(ui.err) + "</p>";
  if (ui.ok) html += '<p class="ok">' + esc(ui.ok) + "</p>";
  if (ui.forgot) {
    html += forgotHtml();
  } else if (ui.adminReset) {
    html += adminResetHtml();
  } else if (ui.recovery) {
    html += recoveryHtml();
  } else if (ui.authTab === "login") {
    html += '<form onsubmit="return doLogin(event)">' +
      '<label><span>মোবাইল নম্বর</span><input id="li-phone" required placeholder="০১৭XXXXXXXX" inputmode="tel"></label>' +
      '<label><span>পাসওয়ার্ড</span><input id="li-pass" type="password" required placeholder="আপনার পাসওয়ার্ড"></label>' +
      '<button type="submit" style="width:100%">লগইন করুন</button>' +
      '<p style="text-align:center;margin-top:10px"><a href="#" onclick="openForgot();return false" style="color:#14632e;font-weight:600">পাসওয়ার্ড ভুলে গেছেন? (শুধু দাতাদের জন্য)</a></p>' +
      '<p style="text-align:center;margin-top:6px"><a href="#" onclick="openAdminReset();return false" class="dim" style="font-weight:600">অ্যাডমিন পাসওয়ার্ড রিসেট (মূল অ্যাডমিনের অনুমোদন)</a></p>' +
      '<p style="text-align:center;margin-top:6px"><a href="#" onclick="openRecovery();return false" class="dim" style="font-weight:600">মূল অ্যাডমিন পুনরুদ্ধার (ইমেইল যাচাই)</a></p>' +
      '<p class="dim" style="text-align:center;margin-top:6px">দাতা ও অ্যাডমিন — সবাই একই জায়গা থেকে লগইন করেন। দাতা পাসওয়ার্ড ভুলে গেলে কোড ছাড়াই সরাসরি নতুন পাসওয়ার্ড বসাতে পারেন। অ্যাডমিন নিজে নিজে রিসেট করতে পারেন না — অ্যাডমিনের রিসেটে মূল অ্যাডমিনের অনুমোদন লাগে, আর মূল অ্যাডমিনের রিসেট হয় রেজিস্টার্ড ইমেইল যাচাই দিয়ে।</p></form>';
  } else {
    html += '<form onsubmit="return doRegister(event)">' +
      '<label><span>আপনার নাম</span><input id="rg-name" required placeholder="পুরো নাম লিখুন"></label>' +
      '<label><span>মোবাইল নম্বর (লগইন আইডি)</span><input id="rg-phone" required placeholder="০১৭XXXXXXXX" inputmode="tel" maxlength="11"><small class="dim">মোবাইল নম্বর অবশ্যই ১১ ডিজিটের হতে হবে — কম হলে অ্যাকাউন্ট তৈরি হবে না।</small></label>' +
      '<label><span>পাসওয়ার্ড</span><input id="rg-pass" type="password" required minlength="4" placeholder="কমপক্ষে ৪ অক্ষর"></label>' +
      '<label><span>ঠিকানা</span><input id="rg-addr" placeholder="গ্রাম / এলাকা, উপজেলা, জেলা"></label>' +
      '<button type="submit" style="width:100%">অ্যাকাউন্ট তৈরি করুন</button>' +
      '<p class="dim" style="text-align:center;margin-top:10px">অ্যাকাউন্ট তৈরি করে লগইন করলেই নিজের সংকল্প (মোট দানের পরিমাণ) ঠিক করে কিস্তিতে দান দিতে পারবেন।</p></form>';
  }
  html += "</section></main>";
  document.getElementById("app").innerHTML = html;
}
function setAuthTab(t) { ui.authTab = t; ui.err = ""; ui.forgot = false; ui.adminReset = false; ui.recovery = false; render(); }
function findByPhone(phone) {
  var normalized = normalizePhoneDigits(phone);
  for (var i = 0; i < db.accounts.length; i++) if (db.accounts[i].phone === normalized || db.accounts[i].phone === phone) return db.accounts[i];
  return null;
}
function doSetup(e) {
  e.preventDefault();
  var name = document.getElementById("su-name").value.trim();
  var rawPhone = document.getElementById("su-phone").value.trim();
  var phoneErr = mobileNumberError(rawPhone);
  if (phoneErr) { ui.err = phoneErr; render(); return false; }
  var phone = normalizePhoneDigits(rawPhone);
  var email = document.getElementById("su-email").value.trim().toLowerCase();
  if (!emailValid(email)) { ui.err = "সঠিক ইমেইল ঠিকানা লিখুন (যেমন: name@example.com)।"; render(); return false; }
  var pass = document.getElementById("su-pass").value;
  var addr = document.getElementById("su-addr").value.trim();
  if (findByPhone(phone)) { ui.err = "এই মোবাইল নম্বর দিয়ে ইতিমধ্যে একটি অ্যাকাউন্ট আছে।"; render(); return false; }
  ui.setupPending = { name: name, phone: phone, email: email, password: pass, address: addr };
  issueEmailCode(phone, "setup");
  save();
  ui.setupStep = 2; ui.err = ""; render();
  return false;
}
function doSetupVerify(e) {
  e.preventDefault();
  var p = ui.setupPending;
  if (!p) { ui.err = "আগে তথ্য দিয়ে যাচাই কোড পাঠান।"; ui.setupStep = 1; render(); return false; }
  var entered = document.getElementById("su-code").value.trim();
  var err = checkEmailCode(p.phone, "setup", entered);
  if (err) { ui.err = err; save(); render(); return false; }
  if (findByPhone(p.phone)) { ui.err = "এই মোবাইল নম্বর দিয়ে ইতিমধ্যে একটি অ্যাকাউন্ট আছে।"; render(); return false; }
  var acc = { id: db.nextId++, name: p.name, phone: p.phone, email: p.email, password: p.password, address: p.address, role: "admin", main: true };
  db.accounts.push(acc); db.sessionId = acc.id;
  logReset(acc, "মূল অ্যাডমিন অ্যাকাউন্ট তৈরি (ইমেইল যাচাই সম্পন্ন)", "ইমেইল " + p.email + " যাচাইয়ের পর মূল অ্যাডমিন অ্যাকাউন্ট তৈরি হয়েছে।");
  ui.setupPending = null; ui.setupStep = 1;
  save();
  ui.view = "admin"; render(); showSplash(acc.name);
  return false;
}
function doRegister(e) {
  e.preventDefault();
  var name = document.getElementById("rg-name").value.trim();
  var rawPhone = document.getElementById("rg-phone").value.trim();
  var phoneErr = mobileNumberError(rawPhone);
  if (phoneErr) { ui.err = phoneErr; render(); return false; }
  var phone = normalizePhoneDigits(rawPhone);
  var pass = document.getElementById("rg-pass").value;
  var addr = document.getElementById("rg-addr").value.trim();
  if (findByPhone(phone)) { ui.err = "এই মোবাইল নম্বর দিয়ে ইতিমধ্যে একটি অ্যাকাউন্ট আছে — লগইন করুন।"; render(); return false; }
  var acc = { id: db.nextId++, name: name, phone: phone, password: pass, address: addr, role: "donor", main: false };
  db.accounts.push(acc); db.sessionId = acc.id; save();
  ui.view = "mine"; render(); showSplash(acc.name);
  return false;
}
function doLogin(e) {
  e.preventDefault();
  var phone = document.getElementById("li-phone").value.trim();
  var pass = document.getElementById("li-pass").value;
  var acc = findByPhone(phone);
  if (!acc) { ui.err = "এই মোবাইল নম্বর দিয়ে কোনো অ্যাকাউন্ট নেই — আগে রেজিস্ট্রেশন করুন।"; render(); return false; }
  if (resetLocked(acc)) { ui.err = "পরপর ৩ বার ভুল রিসেট কোড দেওয়ায় এই অ্যাকাউন্টটি সাময়িকভাবে লক হয়ে আছে — ৩০ মিনিট পর আবার চেষ্টা করুন, অথবা মূল অ্যাডমিনের সঙ্গে যোগাযোগ করুন।"; render(); return false; }
  if (acc.password !== pass) { ui.err = "পাসওয়ার্ড মিলছে না — আবার চেষ্টা করুন।"; render(); return false; }
  db.sessionId = acc.id; save();
  ui.view = acc.role === "admin" ? "admin" : "mine";
  render(); showSplash(acc.name);
  return false;
}
function doLogout() { db.sessionId = null; save(); ui.err = ""; ui.ok = ""; render(); }

/* --------------------------- পাসওয়ার্ড রিসেট --------------------------- */
function openForgot() { ui.forgot = true; ui.adminReset = false; ui.recovery = false; ui.err = ""; ui.ok = ""; render(); }
function closeForgot() { ui.forgot = false; ui.err = ""; ui.ok = ""; render(); }
function openAdminReset() { ui.adminReset = true; ui.forgot = false; ui.recovery = false; ui.err = ""; ui.ok = ""; render(); }
function closeAdminReset() { ui.adminReset = false; ui.err = ""; ui.ok = ""; render(); }
function openRecovery() { ui.recovery = true; ui.forgot = false; ui.adminReset = false; ui.recMode = "email"; ui.recEmailStep = 1; ui.recStep = 1; ui.err = ""; ui.ok = ""; render(); }
function closeRecovery() { ui.recovery = false; ui.err = ""; ui.ok = ""; render(); }
function setRecMode(m) { ui.recMode = m; ui.err = ""; render(); }
function forgotHtml() {
  var h = '<h2 class="display" style="font-size:19px;margin-bottom:8px">পাসওয়ার্ড ভুলে গেছেন?</h2>' +
    '<p class="dim" style="margin-bottom:12px">এই ব্যবস্থাটি <strong>শুধু দাতাদের জন্য</strong>। কোনো কোড লাগবে না — আপনার অ্যাকাউন্টের মোবাইল নম্বর আর নতুন পাসওয়ার্ড দিলেই পাসওয়ার্ড বদলে যাবে। বদলালে আপনি সব ডিভাইস থেকে লগআউট হয়ে যাবেন; নতুন পাসওয়ার্ড দিয়ে আবার লগইন করতে হবে। অ্যাডমিনরা এখান থেকে রিসেট করতে পারবেন না — তাঁদের জন্য আলাদা অংশ আছে।</p>' +
    '<form onsubmit="return doResetDirect(event)">' +
    '<label><span>মোবাইল নম্বর</span><input id="rs-phone" required placeholder="০১৭XXXXXXXX" inputmode="tel"></label>' +
    '<label><span>নতুন পাসওয়ার্ড</span><input id="rs-new" type="password" required minlength="4" placeholder="কমপক্ষে ৪ অক্ষর"></label>' +
    '<label><span>নতুন পাসওয়ার্ড আবার লিখুন</span><input id="rs-confirm" type="password" required placeholder="নতুন পাসওয়ার্ডটি আবার লিখুন"></label>' +
    '<button type="submit" style="width:100%">নতুন পাসওয়ার্ড বসান</button></form>';
  h += '<p style="text-align:center;margin-top:10px"><a href="#" onclick="closeForgot();return false" class="dim" style="font-weight:600">লগইনে ফিরে যান</a></p>';
  return h;
}
function doResetDirect(e) {
  e.preventDefault();
  var phone = document.getElementById("rs-phone").value.trim();
  var np = document.getElementById("rs-new").value;
  var cp = document.getElementById("rs-confirm").value;
  var acc = findByPhone(phone);
  if (!acc) { ui.err = "এই মোবাইল নম্বর দিয়ে কোনো অ্যাকাউন্ট নেই — নম্বরটি ঠিক আছে কিনা দেখুন।"; render(); return false; }
  if (acc.role === "admin") {
    logReset(acc, "অ্যাডমিনের সরাসরি রিসেট চেষ্টা আটকানো হয়েছে", "অ্যাডমিন অ্যাকাউন্টে কোড ছাড়া সরাসরি রিসেট করা যায় না।"); save();
    ui.err = acc.main
      ? "মূল অ্যাডমিনের পাসওয়ার্ড এভাবে বদলানো যাবে না — নিচের \"মূল অ্যাডমিন পুনরুদ্ধার (ইমেইল যাচাই)\" অংশ ব্যবহার করুন।"
      : "অ্যাডমিন নিজে নিজে পাসওয়ার্ড রিসেট করতে পারবেন না। \"অ্যাডমিন পাসওয়ার্ড রিসেট\" অংশ থেকে অনুমোদনের অনুরোধ পাঠান — মূল অ্যাডমিন অনুমোদন দিলেই কেবল পাসওয়ার্ড বদলাবে।";
    render(); return false;
  }
  if (np !== cp) { ui.err = "নতুন পাসওয়ার্ড দুইবার একই লিখুন।"; render(); return false; }
  acc.password = np;
  acc.lockUntil = 0;
  delete db.resets[normalizePhoneDigits(phone)];
  if (db.sessionId === acc.id) db.sessionId = null;
  logReset(acc, "দাতার পাসওয়ার্ড রিসেট সফল (কোড ছাড়া সরাসরি)", "মোবাইল নম্বর + নতুন পাসওয়ার্ড দিয়ে সরাসরি রিসেট; অ্যাকাউন্ট লগআউট হয়েছে।");
  save();
  ui.forgot = false; ui.err = "";
  ui.ok = "আপনার পাসওয়ার্ড বদলে গেছে। এবার নতুন পাসওয়ার্ড দিয়ে লগইন করুন।";
  render();
  return false;
}
function adminResetHtml() {
  var h = '<h2 class="display" style="font-size:19px;margin-bottom:8px">অ্যাডমিন পাসওয়ার্ড রিসেট</h2>';
  if (ui.resetStep === 3) {
    h += '<p class="ok">আপনার অনুরোধ মূল অ্যাডমিনের কাছে পাঠানো হয়েছে। নিরাপত্তার জন্য অ্যাডমিন নিজে নিজে পাসওয়ার্ড বদলাতে পারেন না — মূল অ্যাডমিন অনুমোদন দিয়ে নতুন পাসওয়ার্ড বসিয়ে দিলেই কেবল বদলাবে। অনুগ্রহ করে মূল অ্যাডমিনের সঙ্গে যোগাযোগ করুন।</p>';
  } else {
    h += '<p class="dim" style="margin-bottom:12px">নিরাপত্তার জন্য অ্যাডমিন (মূল অ্যাডমিন ছাড়া) নিজে নিজে পাসওয়ার্ড রিসেট করতে পারেন না। আপনার অ্যাডমিন অ্যাকাউন্টের মোবাইল নম্বরটি লিখুন — অনুরোধটি মূল অ্যাডমিনের কাছে যাবে, তিনি অনুমোদন দিয়ে নতুন পাসওয়ার্ড বসিয়ে দিলেই কেবল বদলাবে। মূল অ্যাডমিন হলে "মূল অ্যাডমিন পুনরুদ্ধার (ইমেইল যাচাই)" অংশ ব্যবহার করুন।</p>' +
      '<form onsubmit="return doAdminResetRequest(event)">' +
      '<label><span>অ্যাডমিন অ্যাকাউন্টের মোবাইল নম্বর</span><input id="ar-phone" required placeholder="০১৭XXXXXXXX" inputmode="tel"></label>' +
      '<button type="submit" style="width:100%">অনুমোদনের অনুরোধ পাঠান</button></form>';
  }
  h += '<p style="text-align:center;margin-top:10px"><a href="#" onclick="closeAdminReset();return false" class="dim" style="font-weight:600">লগইনে ফিরে যান</a></p>';
  return h;
}
function doAdminResetRequest(e) {
  e.preventDefault();
  var phone = document.getElementById("ar-phone").value.trim();
  var acc = findByPhone(phone);
  if (!acc) { ui.err = "এই মোবাইল নম্বর দিয়ে কোনো অ্যাকাউন্ট নেই — নম্বরটি ঠিক আছে কিনা দেখুন।"; render(); return false; }
  if (acc.role !== "admin") { ui.err = "এটি দাতার অ্যাকাউন্ট — দাতারা \"পাসওয়ার্ড ভুলে গেছেন?\" অংশ থেকে সরাসরি নতুন পাসওয়ার্ড বসাতে পারেন, কোনো কোড লাগে না।"; render(); return false; }
  if (acc.main) {
    logReset(acc, "মূল অ্যাডমিনের অনুমোদন-রিসেট চেষ্টা আটকানো হয়েছে", "মূল অ্যাডমিনের জন্য ইমেইল যাচাইয়ের পুনরুদ্ধার বাধ্যতামূলক।"); save();
    ui.err = "মূল অ্যাডমিনের পাসওয়ার্ড এভাবে বদলানো যাবে না — \"মূল অ্যাডমিন পুনরুদ্ধার (ইমেইল যাচাই)\" অংশে যান।"; render(); return false;
  }
  if (resetLocked(acc)) { ui.err = RESET_LOCK_MSG; render(); return false; }
  var hasPending = db.requests.some(function (r) { return r.accountId === acc.id && r.status === "pending"; });
  if (!hasPending) db.requests.push({ id: db.nextId++, accountId: acc.id, status: "pending", device: deviceInfo(), at: Date.now() });
  logReset(acc, "অ্যাডমিন রিসেট অনুমোদনের অনুরোধ", hasPending ? "আগের অনুরোধটি এখনো অনুমোদনের অপেক্ষায় আছে।" : "অনুরোধটি মূল অ্যাডমিনের অনুমোদনের অপেক্ষায় রাখা হয়েছে।");
  save();
  ui.resetStep = 3; ui.err = ""; render();
  return false;
}
function recoveryHtml() {
  var h = '<h2 class="display" style="font-size:19px;margin-bottom:8px">মূল অ্যাডমিন পুনরুদ্ধার</h2>' +
    '<div class="tabs" style="margin-bottom:12px">' +
    '<button type="button" class="' + (ui.recMode === "email" ? "on" : "") + '" onclick="setRecMode(\'email\')">ইমেইল যাচাই দিয়ে রিসেট</button>' +
    '<button type="button" class="' + (ui.recMode === "strict" ? "on" : "") + '" onclick="setRecMode(\'strict\')">কড়া পুনরুদ্ধার (OTP + নিরাপত্তা প্রশ্ন)</button></div>';
  if (ui.recMode === "email") {
    h += '<p class="dim" style="margin-bottom:12px">মূল অ্যাডমিনের মোবাইল নম্বর দিলে তাঁর রেজিস্টার্ড ইমেইলে একটি ৬ সংখ্যার যাচাই কোড যাবে এবং রিসেটের নোটিফিকেশনটি লগে লেখা থাকবে। কোডটি মিললেই নতুন পাসওয়ার্ড বসানো যাবে — সফল হলেই সব ডিভাইস থেকে সঙ্গে সঙ্গে লগআউট হয়ে যাবে। কোডের মেয়াদ ১০ মিনিট, এবং কোডটি অ্যাপের ভেতরে কোথাও দেখানো হয় না। অ্যাকাউন্টে ইমেইল সেট করা না থাকলে এই পথ কাজ করবে না।</p>';
    if (ui.recEmailStep === 1) {
      h += '<form onsubmit="return doEmailResetRequest(event)">' +
        '<label><span>মূল অ্যাডমিনের মোবাইল নম্বর</span><input id="em-phone" required placeholder="০১৭XXXXXXXX" inputmode="tel"></label>' +
        '<button type="submit" style="width:100%">ইমেইলে যাচাই কোড পাঠান</button></form>';
    } else {
      h += '<p class="ok">যাচাই কোড তৈরি হয়েছে — কোডটি মূল অ্যাডমিনের রেজিস্টার্ড ইমেইলে যাওয়ার কথা, এবং রিসেটের নোটিফিকেশন লগে লেখা হয়েছে। কোডের মেয়াদ ১০ মিনিট।</p>' +
        emailServiceNotice() +
        '<form onsubmit="return doEmailReset(event)">' +
        '<label><span>মোবাইল নম্বর</span><input id="em-phone2" required inputmode="tel" value="' + esc(ui.recPhone) + '"></label>' +
        '<label><span>ইমেইলে আসা যাচাই কোড (মেয়াদ ১০ মিনিট)</span><input id="em-code" required placeholder="৬ সংখ্যার কোড" inputmode="numeric"></label>' +
        '<label><span>নতুন পাসওয়ার্ড</span><input id="em-new" type="password" required minlength="4" placeholder="কমপক্ষে ৪ অক্ষর"></label>' +
        '<label><span>নতুন পাসওয়ার্ড আবার লিখুন</span><input id="em-confirm" type="password" required placeholder="নতুন পাসওয়ার্ডটি আবার লিখুন"></label>' +
        '<button type="submit" style="width:100%">পাসওয়ার্ড বদলান</button></form>' +
        '<p style="text-align:center;margin-top:10px"><a href="#" onclick="ui.recEmailStep=1;ui.err=\'\';render();return false" style="color:#14632e;font-weight:600">নতুন কোডের অনুরোধ করুন</a></p>';
    }
  } else {
    h += '<p class="dim" style="margin-bottom:12px">এই পথে তিনটি জিনিসই মিলতে হবে: (১) রেজিস্টার্ড মোবাইলে আসা OTP, (২) আগে থেকে সেট করা পুনরুদ্ধার ইমেইল, (৩) নিরাপত্তা প্রশ্নের উত্তর। সফল হলেই সব ডিভাইস থেকে সঙ্গে সঙ্গে লগআউট হয়ে যাবে। প্রতিটি চেষ্টা লগে লেখা থাকে। (এই অ্যাপ থেকে এসএমএস যায় না, তাই OTP আপাতত নম্বরে পৌঁছাবে না — এসএমএস গেটওয়ে যুক্ত হলেই এই পথ পুরোপুরি চালু হবে। পুনরুদ্ধার ইমেইল ও নিরাপত্তা প্রশ্ন আগে থেকে অ্যাডমিন প্যানেলের সেটিংসে সেট করা থাকতে হবে।)</p>';
    if (ui.recStep === 1) {
      h += '<form onsubmit="return doRecOtpRequest(event)">' +
        '<label><span>মূল অ্যাডমিনের মোবাইল নম্বর</span><input id="rc-phone" required placeholder="০১৭XXXXXXXX" inputmode="tel"></label>' +
        '<button type="submit" style="width:100%">OTP-এর অনুরোধ করুন</button></form>';
    } else {
      h += '<form onsubmit="return doRecReset(event)">' +
        '<label><span>মোবাইল নম্বর</span><input id="rc-phone2" required inputmode="tel" value="' + esc(ui.recPhone) + '"></label>' +
        '<label><span>মোবাইলে আসা OTP (মেয়াদ ৫ মিনিট)</span><input id="rc-otp" required placeholder="৬ সংখ্যার OTP" inputmode="numeric"></label>' +
        '<label><span>পুনরুদ্ধার ইমেইল</span><input id="rc-email" type="email" required placeholder="আগে সেট করা ইমেইল ঠিকানা"></label>' +
        '<label><span>নিরাপত্তা প্রশ্নের উত্তর</span><input id="rc-answer" required placeholder="সেট করার সময় দেওয়া উত্তরটি হুবহু লিখুন"></label>' +
        '<label><span>নতুন পাসওয়ার্ড</span><input id="rc-new" type="password" required minlength="4" placeholder="কমপক্ষে ৪ অক্ষর"></label>' +
        '<label><span>নতুন পাসওয়ার্ড আবার লিখুন</span><input id="rc-confirm" type="password" required placeholder="নতুন পাসওয়ার্ডটি আবার লিখুন"></label>' +
        '<button type="submit" style="width:100%">পাসওয়ার্ড বদলান</button></form>' +
        '<p style="text-align:center;margin-top:10px"><a href="#" onclick="ui.recStep=1;ui.err=\'\';render();return false" style="color:#14632e;font-weight:600">নতুন OTP-এর অনুরোধ করুন</a></p>';
    }
  }
  h += '<p style="text-align:center;margin-top:10px"><a href="#" onclick="closeRecovery();return false" class="dim" style="font-weight:600">লগইনে ফিরে যান</a></p>';
  return h;
}
function doEmailResetRequest(e) {
  e.preventDefault();
  var phone = document.getElementById("em-phone").value.trim();
  var acc = findByPhone(phone);
  if (!acc || acc.role !== "admin" || !acc.main) {
    ui.err = "এই নম্বরটি মূল অ্যাডমিনের অ্যাকাউন্ট নয়। দাতারা \"পাসওয়ার্ড ভুলে গেছেন?\" অংশ ব্যবহার করুন; অন্য অ্যাডমিনদের রিসেটে মূল অ্যাডমিনের অনুমোদন লাগে।"; render(); return false;
  }
  if (!acc.email) {
    logReset(acc, "মূল অ্যাডমিন ইমেইল রিসেট ব্যর্থ — ইমেইল সেট করা নেই", "অ্যাকাউন্টে কোনো ইমেইল ঠিকানা সেট করা ছিল না।"); save();
    ui.err = "এই মূল অ্যাডমিন অ্যাকাউন্টে কোনো ইমেইল ঠিকানা সেট করা নেই — তাই ইমেইল যাচাইয়ে রিসেট করা যাচ্ছে না। লগইন করতে পারলে অ্যাডমিন প্যানেলের \"ব্যবহারকারী\" অংশে নিজের অ্যাকাউন্টে ইমেইল বসান।"; render(); return false;
  }
  issueEmailCode(acc.phone, "reset");
  logReset(acc, "মূল অ্যাডমিনের ইমেইল রিসেট — নোটিফিকেশন", "রেজিস্টার্ড ইমেইলে (" + acc.email + ") যাচাই কোড পাঠানোর নোটিফিকেশন রেকর্ড হয়েছে; কোডের মেয়াদ ১০ মিনিট। (ইমেইল সার্ভিস যুক্ত না থাকায় কোডটি আসলে পাঠানো যায়নি এবং অ্যাপে কোথাও দেখানো হয় না।)");
  save();
  ui.recPhone = acc.phone; ui.recEmail = acc.email; ui.recEmailStep = 2; ui.err = ""; render();
  return false;
}
function doEmailReset(e) {
  e.preventDefault();
  var phone = document.getElementById("em-phone2").value.trim();
  var code = document.getElementById("em-code").value.trim();
  var np = document.getElementById("em-new").value;
  var cp = document.getElementById("em-confirm").value;
  var acc = findByPhone(phone);
  if (!acc || acc.role !== "admin" || !acc.main) { ui.err = "এই নম্বরটি মূল অ্যাডমিনের অ্যাকাউন্ট নয়।"; render(); return false; }
  var err = checkEmailCode(acc.phone, "reset", code);
  if (err) {
    logReset(acc, "মূল অ্যাডমিন ইমেইল রিসেট ব্যর্থ — কোড মেলেনি", err); save();
    ui.err = err; render(); return false;
  }
  if (np !== cp) { ui.err = "নতুন পাসওয়ার্ড দুইবার একই লিখুন।"; render(); return false; }
  acc.password = np;
  acc.lockUntil = 0;
  db.sessionId = null;
  logReset(acc, "মূল অ্যাডমিনের পাসওয়ার্ড রিসেট সফল (ইমেইল যাচাই)", "রেজিস্টার্ড ইমেইল (" + acc.email + ") যাচাই সম্পন্ন; সব ডিভাইস থেকে লগআউট হয়েছে।");
  save();
  ui.recovery = false; ui.recEmailStep = 1; ui.err = "";
  ui.ok = "মূল অ্যাডমিনের পাসওয়ার্ড বদলে গেছে এবং সব ডিভাইস থেকে লগআউট হয়ে গেছে। এবার নতুন পাসওয়ার্ড দিয়ে লগইন করুন।";
  render();
  return false;
}
function doRecOtpRequest(e) {
  e.preventDefault();
  var phone = document.getElementById("rc-phone").value.trim();
  var acc = findByPhone(phone);
  if (!acc || acc.role !== "admin" || !acc.main) {
    ui.err = "এই নম্বরটি মূল অ্যাডমিনের অ্যাকাউন্ট নয়। দাতারা \"পাসওয়ার্ড ভুলে গেছেন?\" অংশ ব্যবহার করুন; অন্য অ্যাডমিনদের রিসেটে মূল অ্যাডমিনের অনুমোদন লাগে।"; render(); return false;
  }
  if (resetLocked(acc)) { ui.err = RESET_LOCK_MSG; render(); return false; }
  if (!db.recovery.email || !db.recovery.answer) {
    logReset(acc, "মূল অ্যাডমিন পুনরুদ্ধার ব্যর্থ — তথ্য সেট করা নেই", "পুনরুদ্ধার ইমেইল / নিরাপত্তা প্রশ্ন আগে থেকে সেট করা ছিল না।"); save();
    ui.err = "পুনরুদ্ধার ইমেইল ও নিরাপত্তা প্রশ্ন আগে থেকে সেট করা নেই — তাই এই পথে রিসেট করা যাচ্ছে না। লগইন করতে পারলে অ্যাডমিন প্যানেলের সেটিংসে গিয়ে এগুলো সেট করুন।"; render(); return false;
  }
  var key = normalizePhoneDigits(phone);
  var existing = db.resets[key];
  if (existing && existing.exp > Date.now() && existing.at > Date.now() - 60000) {
    ui.err = "কিছুক্ষণ আগেই একটি OTP তৈরি হয়েছে — এক মিনিট অপেক্ষা করে আবার চেষ্টা করুন।"; render(); return false;
  }
  var code = String(Math.floor(100000 + Math.random() * 900000));
  db.resets[key] = { code: code, exp: Date.now() + 5 * 60 * 1000, at: Date.now(), attempts: 0 };
  logReset(acc, "মূল অ্যাডমিনের OTP-এর অনুরোধ", "কড়া পুনরুদ্ধারের জন্য ৫ মিনিট মেয়াদের OTP তৈরি হয়েছে (OTP অ্যাপে কোথাও দেখানো হয় না)।");
  save();
  ui.recPhone = phone; ui.recStep = 2; ui.err = ""; render();
  return false;
}
function doRecReset(e) {
  e.preventDefault();
  var phone = document.getElementById("rc-phone2").value.trim();
  var otp = document.getElementById("rc-otp").value.trim();
  var email = document.getElementById("rc-email").value.trim();
  var answer = document.getElementById("rc-answer").value.trim();
  var np = document.getElementById("rc-new").value;
  var cp = document.getElementById("rc-confirm").value;
  var acc = findByPhone(phone);
  if (!acc || acc.role !== "admin" || !acc.main) { ui.err = "এই নম্বরটি মূল অ্যাডমিনের অ্যাকাউন্ট নয়।"; render(); return false; }
  if (resetLocked(acc)) { ui.err = RESET_LOCK_MSG; render(); return false; }
  var key = normalizePhoneDigits(phone);
  var r = db.resets[key];
  if (!r) { ui.err = "কোনো সক্রিয় OTP নেই — আগে OTP-এর অনুরোধ করুন।"; render(); return false; }
  if (r.exp < Date.now()) { ui.err = "OTP-টির মেয়াদ শেষ হয়ে গেছে (৫ মিনিট) — নতুন OTP-এর অনুরোধ করুন।"; render(); return false; }
  if (r.code !== otp) { ui.err = wrongCode(acc, r); render(); return false; }
  var emailOk = db.recovery.email.trim().toLowerCase() === email.toLowerCase();
  var answerOk = db.recovery.answer.trim().toLowerCase().replace(/\s+/g, " ") === answer.toLowerCase().replace(/\s+/g, " ");
  if (!emailOk || !answerOk) {
    logReset(acc, "মূল অ্যাডমিন পুনরুদ্ধার ব্যর্থ — ইমেইল/উত্তর মেলেনি", "OTP ঠিক ছিল, কিন্তু পুনরুদ্ধার ইমেইল অথবা নিরাপত্তা প্রশ্নের উত্তর মেলেনি।"); save();
    ui.err = "পুনরুদ্ধার ইমেইল অথবা নিরাপত্তা প্রশ্নের উত্তর মিলছে না — পাসওয়ার্ড বদলানো হয়নি। দুটোই হুবহু মিলতে হবে।"; render(); return false;
  }
  if (np !== cp) { ui.err = "নতুন পাসওয়ার্ড দুইবার একই লিখুন।"; render(); return false; }
  acc.password = np;
  acc.lockUntil = 0;
  delete db.resets[key];
  db.sessionId = null;
  logReset(acc, "মূল অ্যাডমিনের পাসওয়ার্ড রিসেট সফল", "OTP + পুনরুদ্ধার ইমেইল + নিরাপত্তা প্রশ্নের উত্তর — তিনটিই মিলেছে; সব ডিভাইস থেকে লগআউট হয়েছে।");
  save();
  ui.recovery = false; ui.recStep = 1; ui.err = "";
  ui.ok = "মূল অ্যাডমিনের পাসওয়ার্ড বদলে গেছে এবং সব ডিভাইস থেকে লগআউট হয়ে গেছে। এবার নতুন পাসওয়ার্ড দিয়ে লগইন করুন।";
  render();
  return false;
}

/* ------------------------------ দাতা প্যানেল ------------------------------ */
function renderMine(u) {
  var t = totalsFor(u.id);
  var myPayments = db.payments.filter(function (p) { return p.donorId === u.id; })
    .sort(function (a, b) { return b.id - a.id; });
  var html = "";
  html += '<section class="card"><h2 class="display" style="font-size:22px">' + esc(u.name) + "</h2>" +
    '<p class="dim">মোবাইল: ' + esc(u.phone) + (u.address ? " • ঠিকানা: " + esc(u.address) : "") + "</p></section>";

  html += '<section class="card"><h2 class="display" style="font-size:20px;margin-bottom:10px">আমার সংকল্প</h2>';
  if (ui.err) html += '<p class="err">' + esc(ui.err) + "</p>";
  if (ui.ok) html += '<p class="ok">' + esc(ui.ok) + "</p>";
  if (t.pledge) {
    html += '<div class="grid4">' +
      '<div class="stat"><p>মোট সংকল্প</p><p>' + tk(t.pledged) + "</p></div>" +
      '<div class="stat"><p>দেওয়া হয়েছে</p><p style="color:#15803d">' + tk(t.paid) + "</p></div>" +
      '<div class="stat"><p>যাচাই বাকি</p><p style="color:#b45309">' + tk(t.pending) + "</p></div>" +
      '<div class="stat"><p>বাকি আছে</p><p style="color:#14632e">' + tk(t.remaining) + "</p></div></div>" +
      '<div style="margin-top:12px">' + progress(t.paid, t.pledged) + "</div>";
    if (t.pledge.note) html += '<p class="dim" style="margin-top:6px">মন্তব্য: ' + esc(t.pledge.note) + "</p>";
    if (t.remaining === 0 && t.pledged > 0)
      html += '<p class="ok" style="margin-top:10px">জয় জগন্নাথ! আপনার সংকল্প পূর্ণ হয়েছে — মন্দিরের পক্ষ থেকে অসংখ্য ধন্যবাদ ও প্রণাম।</p>';
  } else {
    html += '<p class="dim" style="margin-bottom:10px">আপনি মোট কত টাকা দান করতে চান, সেই সংকল্পটি ঠিক করুন। তারপর সুবিধামতো কিস্তিতে কিস্তিতে — অথবা একবারে — দিতে পারবেন।</p>';
  }
  html += '<form onsubmit="return doPledge(event)" style="margin-top:12px">' +
    '<label><span>' + (t.pledge ? "সংকল্পের পরিমাণ বদলান (টাকা)" : "মোট সংকল্পের পরিমাণ (টাকা)") + '</span>' +
    '<input id="pl-amount" type="number" min="1" required placeholder="যেমন: ৫০০০" value="' + (t.pledge ? t.pledged : "") + '"></label>' +
    '<label><span>মন্তব্য (ঐচ্ছিক)</span><input id="pl-note" placeholder="যেমন: মন্দিরের ছাদ মেরামতের জন্য" value="' + (t.pledge ? esc(t.pledge.note || "") : "") + '"></label>' +
    '<button type="submit">সংকল্প সংরক্ষণ করুন</button></form></section>';

  if (t.pledge) {
    var acctNum = ui.payMethod === "cash" ? null : db.settings[ui.payMethod];
    html += '<section class="card"><h2 class="display" style="font-size:20px;margin-bottom:6px">কিস্তি জমা দিন</h2>' +
      '<p class="dim" style="margin-bottom:12px">পরের কিস্তি: <strong>' + ordinal(nextNo(u.id)) + "</strong></p>" +
      '<div class="methods">' + METHODS.map(function (m) {
        return '<button type="button" class="' + (ui.payMethod === m.key ? "on" : "") +
          '" onclick="setPayMethod(\'' + m.key + "')\">" + m.label + "</button>";
      }).join("") + "</div>";
    if (ui.payMethod === "cash") {
      html += '<div class="acct"><p class="dim">মন্দিরে সরাসরি নগদ টাকা জমা দিন। জমা দেওয়ার পর এখানে পরিমাণ লিখে সাবমিট করুন — অ্যাডমিন পেয়ে নিশ্চিত করবেন।</p></div>';
    } else {
      html += '<div class="acct"><p class="dim">মন্দিরের ' + methodLabel(ui.payMethod) + ' নম্বর — এই নম্বরে টাকা পাঠান:</p>' +
        '<p class="num">' + esc(acctNum) + "</p>" +
        (String(acctNum).indexOf("XXXX") >= 0 ? '<p class="dim">এটি একটি নমুনা নম্বর — অ্যাডমিন আসল নম্বর বসালে এখানে সেটাই দেখাবে।</p>' : "") + "</div>";
    }
    html += '<form onsubmit="return doPay(event)">' +
      '<label><span>কত টাকা দিচ্ছেন (টাকা)</span><input id="pay-amount" type="number" min="1" required placeholder="যেমন: ১০০০"></label>';
    if (t.remaining > 0)
      html += '<p style="margin-bottom:10px"><a href="#" onclick="fillRemaining(' + t.remaining + ');return false" style="color:#14632e;font-weight:600">বাকি পুরো টাকা একবারে দিন (' + tk(t.remaining) + ")</a></p>";
    if (ui.payMethod !== "cash") {
      html += '<div class="grid2">' +
        '<label><span>লেনদেন নম্বর (ট্রান্সঅ্যাকশন আইডি)</span><input id="pay-trx" placeholder="ট্রান্সঅ্যাকশন আইডিটি লিখুন"></label>' +
        '<label><span>যে নম্বর থেকে পাঠিয়েছেন</span><input id="pay-sender" placeholder="০১৭XXXXXXXX" inputmode="tel"></label></div>';
    }
    html += '<p class="dim" style="margin-bottom:10px">এটি ম্যানুয়াল পেমেন্ট — টাকা পাঠিয়ে লেনদেন নম্বরটি এখানে জমা দিন, অ্যাডমিন যাচাই করে নিশ্চিত করবেন। কোনো অনলাইন পেমেন্ট গেটওয়ে সংযুক্ত নয়।</p>' +
      '<button type="submit" style="width:100%">কিস্তি জমা দিন</button></form></section>';
  }

  html += '<section class="card"><h2 class="display" style="font-size:20px;margin-bottom:6px">আমার কিস্তির ইতিহাস</h2>';
  if (myPayments.length === 0) html += '<p class="dim">এখনো কোনো কিস্তি জমা দেননি।</p>';
  else {
    html += '<p class="dim" style="margin-bottom:6px">কোনো কিস্তির তথ্য ভুল হয়ে থাকলে (যেমন লেনদেন নম্বর) সেটির "তথ্য সংশোধন করুন" চেপে ঠিক করে আবার পাঠাতে পারবেন — শুধু যাচাই বাকি বা বাতিল হওয়া কিস্তির ক্ষেত্রে।</p>';
    html += '<ul class="rows">' + myPayments.map(function (p) { return paymentRow(p, null, true); }).join("") + "</ul>";
  }
  html += "</section>";

  html += '<section class="card"><h2 class="display" style="font-size:20px;margin-bottom:10px">পাসওয়ার্ড বদলান</h2>' +
    '<form onsubmit="return doPassword(event)">' +
    '<label><span>বর্তমান পাসওয়ার্ড</span><input id="pw-cur" type="password" required></label>' +
    '<label><span>নতুন পাসওয়ার্ড</span><input id="pw-new" type="password" required minlength="4"></label>' +
    '<button type="submit" class="ghost">পাসওয়ার্ড বদলান</button></form>' +
    '<p class="dim" style="margin-top:10px">পাসওয়ার্ড ভুলে গেলে লগআউট করে লগইন পাতার "পাসওয়ার্ড ভুলে গেছেন?" অংশে মোবাইল নম্বর আর নতুন পাসওয়ার্ড দিলেই সরাসরি বদলে যাবে — কোনো কোড লাগবে না।</p></section>';
  return html;
}
function setPayMethod(k) { ui.payMethod = k; ui.err = ""; ui.ok = ""; render(); }
function fillRemaining(n) { var el = document.getElementById("pay-amount"); if (el) el.value = n; }
function doPledge(e) {
  e.preventDefault();
  var u = me();
  var amount = Math.round(Number(document.getElementById("pl-amount").value));
  var note = document.getElementById("pl-note").value.trim();
  if (!amount || amount <= 0) { ui.err = "সঠিক টাকার পরিমাণ লিখুন।"; render(); return false; }
  db.pledges[u.id] = { amount: amount, note: note };
  save(); ui.err = ""; ui.ok = "আপনার সংকল্প সংরক্ষণ হয়েছে। জয় জগন্নাথ!"; render();
  return false;
}
function doPay(e) {
  e.preventDefault();
  var u = me();
  var amount = Math.round(Number(document.getElementById("pay-amount").value));
  if (!amount || amount <= 0) { ui.err = "সঠিক টাকার পরিমাণ লিখুন।"; render(); return false; }
  var trx = "", sender = "";
  if (ui.payMethod !== "cash") {
    trx = document.getElementById("pay-trx").value.trim();
    sender = document.getElementById("pay-sender").value.trim();
    if (!trx) { ui.err = "লেনদেন নম্বর (ট্রান্সঅ্যাকশন আইডি) লিখুন — অ্যাডমিন এটি মিলিয়ে যাচাই করবেন।"; render(); return false; }
  }
  var no = nextNo(u.id);
  db.payments.push({ id: db.nextId++, donorId: u.id, no: no, amount: amount, method: ui.payMethod,
    trx: trx, sender: sender, status: "pending", date: Date.now() });
  save(); ui.err = ""; ui.ok = "আপনার " + ordinal(no) + " জমা হয়েছে — অ্যাডমিন যাচাই করে নিশ্চিত করবেন।"; render();
  return false;
}

/* ----------------------------- অ্যাডমিন প্যানেল ----------------------------- */
function renderAdmin(u) {
  var donors = db.accounts.filter(function (a) { return a.role === "donor"; });
  var totalPledged = 0, totalCollected = 0;
  donors.forEach(function (d) { var t = totalsFor(d.id); totalPledged += t.pledged; totalCollected += t.paid; });
  var pending = db.payments.filter(function (p) { return p.status === "pending"; })
    .sort(function (a, b) { return a.id - b.id; });
  var pendingAmount = pending.reduce(function (s, p) { return s + p.amount; }, 0);
  var byId = {};
  db.accounts.forEach(function (a) { byId[a.id] = a; });

  var tabs = [["overview", "সারসংক্ষেপ"], ["summary", "সামারি"], ["verify", "যাচাই" + (pending.length ? " (" + bn(pending.length) + ")" : "")],
    ["donors", "দাতা তালিকা"]];
  if (u.main) tabs.push(["users", "ব্যবহারকারী"]);
  tabs.push(["settings", "সেটিংস"]);
  var html = '<div class="admintabs">' + tabs.map(function (t) {
    return '<button type="button" class="pill ' + (ui.adminTab === t[0] ? "on" : "off") +
      '" onclick="setAdminTab(\'' + t[0] + "')\">" + t[1] + "</button>";
  }).join("") + "</div>";
  if (ui.err) html += '<p class="err">' + esc(ui.err) + "</p>";
  if (ui.ok) html += '<p class="ok">' + esc(ui.ok) + "</p>";

  if (ui.adminTab === "overview") {
    html += '<div class="grid4" style="margin-bottom:18px">' +
      '<div class="stat"><p>মোট দাতা</p><p>' + bn(donors.length) + " জন</p></div>" +
      '<div class="stat"><p>মোট সংকল্প</p><p>' + tk(totalPledged) + "</p></div>" +
      '<div class="stat"><p>মোট সংগ্রহ (নিশ্চিত)</p><p style="color:#15803d">' + tk(totalCollected) + "</p></div>" +
      '<div class="stat"><p>মোট বাকি</p><p style="color:#14632e">' + tk(Math.max(0, totalPledged - totalCollected)) + "</p></div></div>";
    if (pending.length)
      html += '<button type="button" style="width:100%;background:#fffbeb;color:#92400e;border:2px solid #fbbf24;text-align:left" onclick="setAdminTab(\'verify\')">' +
        bn(pending.length) + "টি পেমেন্ট যাচাইয়ের অপেক্ষায় আছে (মোট " + tk(pendingAmount) + ") — দেখতে এখানে চাপ দিন।</button>";
    var pendingApprovals = db.requests.filter(function (r) { return r.status === "pending"; }).length;
    if (pendingApprovals)
      html += '<button type="button" style="width:100%;background:#fef2f2;color:#7f1d1d;border:2px solid #f87171;text-align:left;margin-top:10px" onclick="setAdminTab(\'verify\')">' +
        bn(pendingApprovals) + ' জন অ্যাডমিন পাসওয়ার্ড রিসেটের অনুমোদন চেয়েছেন — মূল অ্যাডমিনের অনুমোদন ছাড়া কোনো অ্যাডমিনের পাসওয়ার্ড বদলাবে না। দেখতে "যাচাই" অংশে যান।</button>';
    var recent = db.payments.slice().sort(function (a, b) { return b.id - a.id; }).slice(0, 30);
    html += '<section class="card" style="margin-top:18px"><h2 class="display" style="font-size:20px;margin-bottom:6px">সাম্প্রতিক পেমেন্টসমূহ</h2>';
    if (!recent.length) html += '<p class="dim">এখনো কোনো পেমেন্ট আসেনি।</p>';
    else html += '<ul class="rows">' + recent.map(function (p) {
      return paymentRow(p, byId[p.donorId] ? byId[p.donorId].name + " • " + byId[p.donorId].phone : "অজানা দাতা");
    }).join("") + "</ul>";
    html += "</section>";
  }

  if (ui.adminTab === "summary") {
    var totalRemaining = Math.max(0, totalPledged - totalCollected);
    var rate = totalPledged > 0 ? Math.round(totalCollected / totalPledged * 100) : null;
    html += '<div class="grid4" style="margin-bottom:18px">' +
      '<div class="stat"><p>মোট দাতা</p><p>' + bn(donors.length) + " জন</p></div>" +
      '<div class="stat"><p>মোট সংকল্প (সব দাতার প্রতিশ্রুতি)</p><p>' + tk(totalPledged) + "</p></div>" +
      '<div class="stat" style="border:2px solid #15803d;background:#f0fdf4"><p style="color:#166534;font-weight:600">মোট টাকা এসেছে (নিশ্চিত সংগ্রহ)</p><p style="color:#15803d">' + tk(totalCollected) + "</p></div>" +
      '<div class="stat"><p>যাচাই বাকি আছে</p><p style="color:#b45309">' + tk(pendingAmount) + '</p><p class="dim" style="font-size:12px">' + bn(pending.length) + "টি কিস্তি যাচাইয়ের অপেক্ষায়</p></div>" +
      '<div class="stat"><p>মোট বাকি (সংকল্প − সংগ্রহ)</p><p style="color:#14632e">' + tk(totalRemaining) + "</p></div>" +
      '<div class="stat"><p>সংগ্রহের হার</p><p>' + (rate === null ? "—" : bn(rate) + "%") + "</p></div></div>";
    html += '<section class="card"><h2 class="display" style="font-size:20px;margin-bottom:6px">মাধ্যম অনুযায়ী মোট সংগ্রহ (নিশ্চিত)</h2><ul class="rows">';
    METHODS.forEach(function (m) {
      var rows = db.payments.filter(function (p) { return p.method === m.key && p.status === "confirmed"; });
      var amt = rows.reduce(function (s, p) { return s + p.amount; }, 0);
      html += '<li><div style="font-weight:600">' + m.label + ' <span class="dim" style="font-weight:400;font-size:13px">' + bn(rows.length) + 'টি কিস্তি</span></div><div class="display" style="font-size:17px;font-weight:700">' + tk(amt) + "</div></li>";
    });
    html += '<li><div style="font-weight:700">সর্বমোট এসেছে</div><div class="display" style="font-size:19px;font-weight:700;color:#15803d">' + tk(totalCollected) + "</div></li></ul></section>";
    html += '<section class="card"><h2 class="display" style="font-size:20px;margin-bottom:6px">দাতা অনুযায়ী সামারি — কে কত দিলেন</h2>' +
      '<p class="dim" style="margin-bottom:10px">প্রতিটি দাতার সংকল্প, দেওয়া (নিশ্চিত), যাচাই বাকি ও বাকি পরিমাণ — শেষে সবার যোগফল।</p>';
    if (!donors.length) html += '<p class="dim">এখনো কোনো দাতা অ্যাকাউন্ট নেই।</p>';
    else {
      html += donors.map(function (d, i) {
        var t = totalsFor(d.id);
        return '<div style="border:1px solid #b7dec0;border-radius:12px;padding:12px;margin-bottom:10px">' +
          '<div style="display:flex;justify-content:space-between;gap:10px;flex-wrap:wrap"><p style="font-weight:600">' + bn(i + 1) + ". " + esc(d.name) + '</p>' +
          '<p style="font-weight:700;color:#15803d">দিয়েছেন ' + tk(t.paid) + "</p></div>" +
          '<p class="dim">মোবাইল: ' + esc(d.phone) + (d.address ? " • " + esc(d.address) : "") + "</p>" +
          '<div class="grid4" style="margin-top:8px">' +
          '<div class="stat"><p>সংকল্প</p><p style="font-size:17px">' + tk(t.pledged) + "</p></div>" +
          '<div class="stat"><p>দেওয়া (নিশ্চিত)</p><p style="font-size:17px;color:#15803d">' + tk(t.paid) + "</p></div>" +
          '<div class="stat"><p>যাচাই বাকি</p><p style="font-size:17px;color:#b45309">' + tk(t.pending) + "</p></div>" +
          '<div class="stat"><p>বাকি</p><p style="font-size:17px;color:#14632e">' + tk(t.remaining) + "</p></div></div></div>";
      }).join("");
      html += '<div style="border:2px solid #14632e;background:#dcf2e1;border-radius:12px;padding:12px">' +
        '<p class="display" style="font-weight:700;font-size:17px">সর্বমোট যোগফল — ' + bn(donors.length) + " জন দাতা</p>" +
        '<div class="grid4" style="margin-top:8px">' +
        '<div class="stat" style="background:#fdfffc"><p>মোট সংকল্প</p><p style="font-size:17px">' + tk(totalPledged) + "</p></div>" +
        '<div class="stat" style="background:#fdfffc"><p>মোট এসেছে</p><p style="font-size:17px;color:#15803d">' + tk(totalCollected) + "</p></div>" +
        '<div class="stat" style="background:#fdfffc"><p>যাচাই বাকি</p><p style="font-size:17px;color:#b45309">' + tk(pendingAmount) + "</p></div>" +
        '<div class="stat" style="background:#fdfffc"><p>মোট বাকি</p><p style="font-size:17px;color:#14632e">' + tk(totalRemaining) + "</p></div></div></div>";
    }
    html += "</section>";
  }

  if (ui.adminTab === "verify") {
    var pendingReqs = db.requests.filter(function (r) { return r.status === "pending"; });
    html += '<section class="card"><h2 class="display" style="font-size:20px;margin-bottom:6px">অ্যাডমিন পাসওয়ার্ড রিসেট — অনুমোদনের অপেক্ষায়</h2>' +
      '<p class="dim" style="margin-bottom:8px">অ্যাডমিন নিজে নিজে পাসওয়ার্ড রিসেট করতে পারেন না। কোনো অ্যাডমিন পাসওয়ার্ড ভুলে গেলে তাঁর অনুরোধ এখানে আসে — শুধু মূল অ্যাডমিন অনুমোদন দিয়ে নতুন পাসওয়ার্ড বসালেই পাসওয়ার্ড বদলাবে; অনুমোদন না দিলে বদলাবে না। প্রতিটি অনুরোধ ও সিদ্ধান্ত লগে লেখা থাকে।</p>';
    if (!pendingReqs.length) html += '<p class="dim">এখন কোনো অ্যাডমিন রিসেট অনুরোধ অপেক্ষায় নেই।</p>';
    else html += '<ul class="rows">' + pendingReqs.map(function (r) {
      var a = null;
      db.accounts.forEach(function (x) { if (x.id === r.accountId) a = x; });
      var h = "<li><div><div style=\"font-weight:600\">" + esc(a ? a.name : "অজানা") + " (অ্যাডমিন)</div>" +
        '<div class="dim">মোবাইল: ' + esc(a ? a.phone : "") + " • অনুরোধ: " + fmtDateTime(r.at) + (r.device ? " • ডিভাইস: " + esc(r.device) : "") + "</div></div>";
      if (u.main) {
        if (ui.approveFor === r.id) {
          h += '<form onsubmit="return doApproveReset(event,' + r.id + ')" style="background:#d9eeda;border-radius:12px;padding:12px;flex-basis:100%">' +
            '<p class="dim" style="margin-bottom:8px">অনুমোদন দিলে ' + esc(a ? a.name : "") + '-এর জন্য নিচের নতুন পাসওয়ার্ডটি চালু হবে। পরিচয় নিশ্চিত না হলে বাতিল করুন।</p>' +
            '<label><span>নতুন পাসওয়ার্ড</span><input id="ap-new" type="password" required minlength="4"></label>' +
            '<div style="display:flex;gap:8px;flex-wrap:wrap"><button type="submit">অনুমোদন দিয়ে পাসওয়ার্ড বসান</button>' +
            '<button type="button" class="red" onclick="doRejectReset(' + r.id + ')">বাতিল করুন</button>' +
            '<button type="button" class="ghost" onclick="toggleApprove(' + r.id + ')">বন্ধ করুন</button></div></form>';
        } else {
          h += '<div><button type="button" onclick="toggleApprove(' + r.id + ')">অনুমোদন / বাতিল</button></div>';
        }
      } else {
        h += '<div class="dim">শুধু মূল অ্যাডমিন অনুমোদন দিতে পারবেন।</div>';
      }
      return h + "</li>";
    }).join("") + "</ul>";
    html += "</section>";
    if (u.main) {
      html += '<section class="card"><h2 class="display" style="font-size:20px;margin-bottom:6px">পাসওয়ার্ড রিসেট লগ (শুধু মূল অ্যাডমিন)</h2>' +
        '<p class="dim" style="margin-bottom:8px">প্রতিটি রিসেট চেষ্টা — কে, কখন, কোন ডিভাইস থেকে — এখানে লেখা থাকে, মূল অ্যাডমিনের ইমেইল রিসেটের নোটিফিকেশনসহ। (এই অ্যাপ থেকে এখনো আসল এসএমএস/ইমেইল যায় না, তাই মূল অ্যাডমিনের নোটিশ হলো এই লগ ও উপরের অপেক্ষমাণ অনুরোধের তালিকা।)</p>';
      if (!db.resetLog.length) html += '<p class="dim">এখনো কোনো রিসেট চেষ্টার লগ নেই।</p>';
      else html += '<ul class="rows">' + db.resetLog.slice(0, 50).map(function (l) {
        return "<li><div><div style=\"font-weight:600\">" + esc(l.event) + "</div>" +
          '<div class="dim">' + (l.name ? esc(l.name) + (l.role === "admin" ? " (অ্যাডমিন)" : " (দাতা)") + " • " + esc(l.phone) + " • " : "") + fmtDateTime(l.at) + "</div>" +
          (l.detail ? '<div class="dim">' + esc(l.detail) + "</div>" : "") +
          (l.device ? '<div class="dim" style="font-size:12px;word-break:break-all">ডিভাইস: ' + esc(l.device) + "</div>" : "") +
          "</div></li>";
      }).join("") + "</ul>";
      html += "</section>";
    }
    html += '<section class="card"><h2 class="display" style="font-size:20px;margin-bottom:6px">যাচাইয়ের অপেক্ষায় থাকা পেমেন্ট</h2>' +
      '<p class="dim" style="margin-bottom:8px">দাতার পাঠানো লেনদেন নম্বরটি নিজের বিকাশ/নগদ/রকেট/ব্যাংক হিসাবের সঙ্গে মিলিয়ে দেখে নিশ্চিত বা বাতিল করুন।</p>';
    if (!pending.length) html += '<p class="dim">যাচাইয়ের অপেক্ষায় কোনো পেমেন্ট নেই। জয় জগন্নাথ!</p>';
    else html += '<ul class="rows">' + pending.map(function (p) {
      var d = byId[p.donorId];
      return "<li><div><div style=\"font-weight:600\">" + esc(d ? d.name : "অজানা দাতা") + " — " + tk(p.amount) + "</div>" +
        '<div class="dim">' + ordinal(p.no) + " • " + methodLabel(p.method) + " • " + fmtDate(p.date) + "</div>" +
        '<div class="dim">দাতার মোবাইল: ' + esc(d ? d.phone : "") + (p.sender ? " • প্রেরক: " + esc(p.sender) : "") + "</div>" +
        (p.trx ? '<div>লেনদেন নম্বর: <strong>' + esc(p.trx) + "</strong></div>" : "") +
        '</div><div style="display:flex;gap:8px;flex-wrap:wrap">' +
        '<button type="button" class="green" onclick="verifyPay(' + p.id + ',true)">নিশ্চিত করুন</button>' +
        '<button type="button" class="red" onclick="verifyPay(' + p.id + ',false)">বাতিল করুন</button></div></li>';
    }).join("") + "</ul>";
    html += "</section>";
  }

  if (ui.adminTab === "donors") {
    html += '<input placeholder="নাম, মোবাইল বা ঠিকানা দিয়ে খুঁজুন" value="' + esc(ui.search) +
      '" oninput="ui.search=this.value;renderDonorList()" aria-label="দাতা খুঁজুন" style="margin-bottom:14px">' +
      '<div id="donor-list">' + donorListHtml() + "</div>";
  }

  if (ui.adminTab === "users" && u.main) {
    var admins = db.accounts.filter(function (a) { return a.role === "admin"; });
    html += '<section class="card"><h2 class="display" style="font-size:20px;margin-bottom:6px">নতুন অ্যাডমিন যোগ করুন</h2>' +
      '<p class="dim" style="margin-bottom:12px">বর্তমানে অ্যাডমিন আছেন ' + bn(admins.length) + " জন — সর্বোচ্চ " + bn(MAX_ADMINS) + " জন থাকতে পারবেন। অ্যাডমিন অ্যাকাউন্টে মোবাইল নম্বরের পাশাপাশি ইমেইল ঠিকানাও আবশ্যক।</p>" +
      '<form onsubmit="return doCreateAdmin(event)"><div class="grid2">' +
      '<label><span>নাম</span><input id="na-name" required></label>' +
      '<label><span>মোবাইল নম্বর</span><input id="na-phone" required inputmode="tel" maxlength="11"><small class="dim">মোবাইল নম্বর অবশ্যই ১১ ডিজিটের হতে হবে — কম হলে অ্যাকাউন্ট তৈরি হবে না।</small></label>' +
      '<label><span>ইমেইল ঠিকানা</span><input id="na-email" type="email" required placeholder="যেমন: name@example.com"></label>' +
      '<label><span>পাসওয়ার্ড</span><input id="na-pass" type="password" required minlength="4"></label></div>' +
      '<button type="submit">অ্যাডমিন অ্যাকাউন্ট তৈরি করুন</button></form></section>';
    html += '<h2 class="display" style="font-size:20px;margin:14px 0 8px">অ্যাডমিনগণ (' + bn(admins.length) + ')</h2><div>' +
      admins.map(function (a) { return userRowHtml(a, u); }).join("") + "</div>";
    html += '<h2 class="display" style="font-size:20px;margin:14px 0 8px">দাতাগণ (' + bn(donors.length) + ')</h2><div>' +
      (donors.length ? donors.map(function (a) { return userRowHtml(a, u); }).join("") : '<p class="dim">এখনো কোনো দাতা অ্যাকাউন্ট নেই।</p>') + "</div>";
  }

  if (ui.adminTab === "settings") {
    html += '<section class="card"><h2 class="display" style="font-size:20px;margin-bottom:6px">মন্দিরের পেমেন্ট নম্বরসমূহ</h2>' +
      '<p class="dim" style="margin-bottom:12px">দাতা কিস্তি দেওয়ার সময় মাধ্যম বেছে নিলে এখানকার নম্বরটাই দেখতে পাবেন। নমুনা নম্বর বদলে মন্দিরের আসল নম্বর বসান।</p>' +
      '<form onsubmit="return doSettings(event)">' +
      '<label><span>বিকাশ নম্বর</span><input id="st-bkash" value="' + esc(db.settings.bkash) + '"></label>' +
      '<label><span>নগদ নম্বর</span><input id="st-nagad" value="' + esc(db.settings.nagad) + '"></label>' +
      '<label><span>রকেট নম্বর</span><input id="st-rocket" value="' + esc(db.settings.rocket) + '"></label>' +
      '<label><span>ব্যাংক অ্যাকাউন্টের বিবরণ</span><textarea id="st-bank" rows="3">' + esc(db.settings.bank) + "</textarea></label>" +
      '<button type="submit">নম্বর সংরক্ষণ করুন</button></form></section>';
    html += '<section class="card"><h2 class="display" style="font-size:20px;margin-bottom:10px">আমার পাসওয়ার্ড বদলান</h2>' +
      '<form onsubmit="return doPassword(event)">' +
      '<label><span>বর্তমান পাসওয়ার্ড</span><input id="pw-cur" type="password" required></label>' +
      '<label><span>নতুন পাসওয়ার্ড</span><input id="pw-new" type="password" required minlength="4"></label>' +
      '<button type="submit" class="ghost">পাসওয়ার্ড বদলান</button></form>' +
      '<p class="dim" style="margin-top:10px">অ্যাডমিন নিজে নিজে ভুলে যাওয়া পাসওয়ার্ড রিসেট করতে পারেন না। পাসওয়ার্ড একেবারে ভুলে গেলে লগআউট করে লগইন পাতার "অ্যাডমিন পাসওয়ার্ড রিসেট" অংশে নম্বর দিন — আপনার অনুরোধ মূল অ্যাডমিনের কাছে যাবে, তিনি অনুমোদন দিলেই কেবল নতুন পাসওয়ার্ড চালু হবে। মূল অ্যাডমিনের নিজের রিসেট হয় রেজিস্টার্ড ইমেইল যাচাই দিয়ে (লগইন পাতার "মূল অ্যাডমিন পুনরুদ্ধার" অংশ) — ইমেইলে কোড যাবে, নোটিফিকেশন লগে থাকবে, কোড মিললেই নতুন পাসওয়ার্ড বসানো যাবে; চাইলে কড়া পথটিও (মোবাইল OTP + পুনরুদ্ধার ইমেইল + নিরাপত্তা প্রশ্ন) আছে। সফল হলেই সব ডিভাইস থেকে লগআউট হয়ে যাবে। মূল অ্যাডমিন "ব্যবহারকারী" অংশ থেকে শুধু দাতাদের পাসওয়ার্ড সরাসরি রিসেট করতে পারেন। দাতারা নিজেরা লগইন পাতা থেকেই কোড ছাড়া সরাসরি রিসেট করতে পারেন।</p></section>';
    if (u.main) {
      html += '<section class="card"><h2 class="display" style="font-size:20px;margin-bottom:6px">মূল অ্যাডমিন পুনরুদ্ধার তথ্য (ইমেইল ও নিরাপত্তা প্রশ্ন)</h2>' +
        '<p class="dim" style="margin-bottom:12px">মূল অ্যাডমিনের পাসওয়ার্ড ভুলে গেলে কড়া পুনরুদ্ধারে এই ইমেইল ও নিরাপত্তা প্রশ্নের উত্তর লাগবে (মোবাইল OTP-এর পাশাপাশি)। এটি অ্যাকাউন্টের মূল ইমেইল থেকে আলাদা অতিরিক্ত সুরক্ষা — মূল ইমেইল যাচাইয়ের সহজ রিসেট পথটি লগইন পাতার "মূল অ্যাডমিন পুনরুদ্ধার" অংশে এমনিতেই আছে। ' +
        (db.recovery.email && db.recovery.answer ? "আপনার পুনরুদ্ধার তথ্য সেট করা আছে।" : "এখনো সেট করা হয়নি — এখনই সেট করে রাখুন, নইলে ভুলে গেলে এই পথে রিসেট করা যাবে না।") +
        ' উত্তর বদলাতে চাইলে নতুন উত্তর লিখুন; আগের উত্তর রাখতে চাইলে উত্তরের ঘর খালি রাখুন।</p>' +
        '<form onsubmit="return doRecoverySettings(event)">' +
        '<label><span>পুনরুদ্ধার ইমেইল</span><input id="rec-email" type="email" required value="' + esc(db.recovery.email) + '" placeholder="যেমন: you@example.com"></label>' +
        '<label><span>নিরাপত্তা প্রশ্ন</span><input id="rec-question" required value="' + esc(db.recovery.question) + '" placeholder="যেমন: আমার প্রিয় ঠাকুরের নাম কী?"></label>' +
        '<label><span>নিরাপত্তা প্রশ্নের উত্তর</span><input id="rec-answer" placeholder="' + (db.recovery.answer ? "আগের উত্তর রাখতে খালি রাখুন" : "উত্তরটি লিখুন") + '"></label>' +
        '<label><span>বর্তমান পাসওয়ার্ড (নিশ্চিত করতে)</span><input id="rec-cur" type="password" required></label>' +
        '<button type="submit">পুনরুদ্ধার তথ্য সংরক্ষণ করুন</button></form></section>';
    }
  }
  return html;
}
function donorListHtml() {
  var q = ui.search.trim().toLowerCase();
  var donors = db.accounts.filter(function (a) {
    if (a.role !== "donor") return false;
    if (!q) return true;
    return a.name.toLowerCase().indexOf(q) >= 0 || a.phone.indexOf(q) >= 0 || (a.address || "").toLowerCase().indexOf(q) >= 0;
  });
  if (!donors.length) return '<section class="card"><p class="dim">কোনো দাতা পাওয়া যায়নি।</p></section>';
  return donors.map(function (d) {
    var t = totalsFor(d.id);
    var pays = db.payments.filter(function (p) { return p.donorId === d.id; })
      .sort(function (a, b) { return b.id - a.id; });
    var h = '<section class="card"><div style="display:flex;justify-content:space-between;gap:10px;flex-wrap:wrap">' +
      '<div><h3 class="display" style="font-size:19px">' + esc(d.name) + '</h3>' +
      '<p class="dim">মোবাইল: ' + esc(d.phone) + (d.address ? " • " + esc(d.address) : "") + "</p></div>" +
      '<button type="button" class="ghost" onclick="toggleDonor(' + d.id + ')">' +
      (ui.expandedDonor === d.id ? "বন্ধ করুন" : "বিস্তারিত দেখুন") + "</button></div>" +
      '<div class="grid2" style="grid-template-columns:repeat(3,1fr);margin-top:12px">' +
      '<div class="stat"><p>সংকল্প</p><p>' + tk(t.pledged) + "</p></div>" +
      '<div class="stat"><p>দিয়েছেন</p><p style="color:#15803d">' + tk(t.paid) + "</p></div>" +
      '<div class="stat"><p>বাকি</p><p style="color:#14632e">' + tk(t.remaining) + "</p></div></div>" +
      '<div style="margin-top:10px">' + progress(t.paid, t.pledged) + "</div>";
    if (ui.expandedDonor === d.id) {
      h += pays.length ? '<ul class="rows">' + pays.map(function (p) { return paymentRow(p); }).join("") + "</ul>"
        : '<p class="dim" style="margin-top:8px">এখনো কোনো কিস্তি দেননি।</p>';
      h += '<form onsubmit="return doRecord(event,' + d.id + ')" style="margin-top:12px;background:#d9eeda;border-radius:12px;padding:12px">' +
        '<p style="font-weight:600;margin-bottom:10px">এই দাতার পক্ষে পেমেন্ট রেকর্ড করুন (সরাসরি পাওয়া টাকা)</p>' +
        '<div class="grid2"><label><span>পরিমাণ (টাকা)</span><input id="rc-amount-' + d.id + '" type="number" min="1" required placeholder="যেমন: ২০০০"></label>' +
        '<label><span>মাধ্যম</span><select id="rc-method-' + d.id + '">' +
        METHODS.map(function (m) { return '<option value="' + m.key + '"' + (m.key === "cash" ? " selected" : "") + ">" + m.label + "</option>"; }).join("") +
        '</select></label>' +
        '<label><span>লেনদেন নম্বর (যদি থাকে)</span><input id="rc-trx-' + d.id + '"></label>' +
        '<label><span>প্রেরকের নম্বর (যদি থাকে)</span><input id="rc-sender-' + d.id + '" inputmode="tel"></label></div>' +
        '<button type="submit">পেমেন্ট রেকর্ড করুন</button></form>';
    }
    return h + "</section>";
  }).join("");
}
function renderDonorList() {
  var el = document.getElementById("donor-list");
  if (el) el.innerHTML = donorListHtml();
}
function toggleDonor(id) { ui.expandedDonor = ui.expandedDonor === id ? null : id; render(); }
function setAdminTab(t) { ui.adminTab = t; ui.err = ""; ui.ok = ""; render(); }
function verifyPay(id, ok) {
  for (var i = 0; i < db.payments.length; i++) {
    if (db.payments[i].id === id) { db.payments[i].status = ok ? "confirmed" : "rejected"; }
  }
  save(); render();
}
function toggleApprove(id) { ui.approveFor = ui.approveFor === id ? null : id; ui.err = ""; render(); }
function doApproveReset(e, reqId) {
  e.preventDefault();
  var np = document.getElementById("ap-new").value;
  var req = null, target = null;
  db.requests.forEach(function (r) { if (r.id === reqId) req = r; });
  if (!req || req.status !== "pending") { ui.err = "অনুরোধটি পাওয়া যাচ্ছে না বা আগেই নিষ্পত্তি হয়ে গেছে।"; render(); return false; }
  db.accounts.forEach(function (a) { if (a.id === req.accountId) target = a; });
  if (!target || target.role !== "admin" || target.main) { ui.err = "এই অনুরোধটি কোনো সাধারণ অ্যাডমিনের নয়।"; render(); return false; }
  target.password = np;
  target.lockUntil = 0;
  delete db.resets[target.phone];
  req.status = "approved"; req.decidedAt = Date.now();
  if (db.sessionId === target.id) db.sessionId = null;
  logReset(target, "অ্যাডমিন রিসেট অনুমোদিত — পাসওয়ার্ড বদলেছে", "অনুমোদন দিয়েছেন মূল অ্যাডমিন।");
  ui.approveFor = null;
  save(); ui.err = ""; ui.ok = target.name + "-এর পাসওয়ার্ড বদলে গেছে — নতুন পাসওয়ার্ডটি তাঁকে নিরাপদে জানিয়ে দিন।"; render();
  return false;
}
function doRejectReset(reqId) {
  var req = null, target = null;
  db.requests.forEach(function (r) { if (r.id === reqId) req = r; });
  if (!req || req.status !== "pending") { ui.err = "অনুরোধটি আগেই নিষ্পত্তি হয়ে গেছে।"; render(); return; }
  db.accounts.forEach(function (a) { if (a.id === req.accountId) target = a; });
  req.status = "rejected"; req.decidedAt = Date.now();
  if (target) logReset(target, "অ্যাডমিন রিসেট অনুরোধ বাতিল", "বাতিল করেছেন মূল অ্যাডমিন। পাসওয়ার্ড বদলায়নি।");
  ui.approveFor = null;
  save(); ui.err = ""; ui.ok = "অনুরোধটি বাতিল করা হয়েছে — পাসওয়ার্ড বদলায়নি।"; render();
}
function doRecord(e, donorId) {
  e.preventDefault();
  var amount = Math.round(Number(document.getElementById("rc-amount-" + donorId).value));
  if (!amount || amount <= 0) { ui.err = "সঠিক টাকার পরিমাণ লিখুন।"; render(); return false; }
  db.payments.push({ id: db.nextId++, donorId: donorId, no: nextNo(donorId), amount: amount,
    method: document.getElementById("rc-method-" + donorId).value,
    trx: document.getElementById("rc-trx-" + donorId).value.trim(),
    sender: document.getElementById("rc-sender-" + donorId).value.trim(),
    status: "confirmed", date: Date.now() });
  save(); ui.err = ""; ui.ok = "পেমেন্ট রেকর্ড হয়েছে (নিশ্চিত)।"; render();
  return false;
}
function userRowHtml(a, current) {
  var t = totalsFor(a.id);
  var h = '<section class="card" style="padding:14px"><div style="display:flex;justify-content:space-between;gap:10px;flex-wrap:wrap"><div>' +
    '<p style="font-weight:600">' + esc(a.name) + " " +
    (a.main ? '<span class="badge main">মূল অ্যাডমিন</span>' : a.role === "admin" ? '<span class="badge role">অ্যাডমিন</span>' : '<span class="badge role">দাতা</span>') +
    (a.id === current.id ? ' <span class="dim">(আপনি)</span>' : "") + "</p>" +
    '<p class="dim">মোবাইল: ' + esc(a.phone) + (a.address ? " • " + esc(a.address) : "") + "</p>" +
    (a.role === "admin" ? '<p class="dim">ইমেইল: ' + (a.email ? esc(a.email) : '<span style="color:#b91c1c;font-weight:600">সেট করা নেই — ইমেইল রিসেটের জন্য বসান</span>') + "</p>" : "") +
    (a.role === "donor" ? '<p class="dim">সংকল্প ' + tk(t.pledged) + " • দেওয়া হয়েছে " + tk(t.paid) + "</p>" : "") +
    "</div>";
  if (!a.main && a.id !== current.id) {
    h += '<div style="display:flex;gap:8px;flex-wrap:wrap;align-items:flex-start">' +
      (a.role === "donor"
        ? '<button type="button" class="ghost" onclick="toggleResetPw(' + a.id + ')">পাসওয়ার্ড রিসেট করুন</button>'
        : '<span class="badge role">অ্যাডমিনের রিসেটে অনুমোদন লাগে — "যাচাই" অংশ দেখুন</span>') +
      (a.role === "donor"
        ? '<button type="button" class="ghost" onclick="setRole(' + a.id + ',\'admin\')">অ্যাডমিন করুন</button>'
        : '<button type="button" class="ghost" onclick="setRole(' + a.id + ',\'donor\')">দাতা করুন</button>');
    if (ui.confirmRemove === a.id) {
      h += '<button type="button" class="red" onclick="removeUser(' + a.id + ')">নিশ্চিত সরান</button>' +
        '<button type="button" class="ghost" onclick="cancelRemove()">বাতিল</button>';
    } else {
      h += '<button type="button" class="ghost" style="color:#b91c1c;border-color:#fca5a5" onclick="askRemove(' + a.id + ')">অ্যাকাউন্ট সরান</button>';
    }
    h += "</div>";
    if (ui.confirmRemove === a.id)
      h += '<p style="color:#b91c1c;font-size:14px;margin-top:8px">এই অ্যাকাউন্ট সরালে তার সংকল্প ও সব কিস্তির রেকর্ডও মুছে যাবে। এটি ফেরানো যাবে না।</p>';
    if (ui.resetPwFor === a.id) {
      h += '<form onsubmit="return doAdminResetPw(event,' + a.id + ')" style="margin-top:12px;background:#d9eeda;border-radius:12px;padding:12px">' +
        '<p style="font-weight:600;margin-bottom:6px">' + esc(a.name) + '-এর জন্য নতুন পাসওয়ার্ড বসান</p>' +
        '<p class="dim" style="margin-bottom:10px">তিনি পাসওয়ার্ড ভুলে গেলে এখানে নতুন পাসওয়ার্ড বসিয়ে তাঁকে জানিয়ে দিন।</p>' +
        '<label><span>নতুন পাসওয়ার্ড</span><input id="rp-new" type="password" required minlength="4"></label>' +
        '<div style="display:flex;gap:8px;flex-wrap:wrap"><button type="submit">নতুন পাসওয়ার্ড বসান</button>' +
        '<button type="button" class="ghost" onclick="toggleResetPw(' + a.id + ')">বাতিল</button></div></form>';
    }
  }
  h += '<div style="margin-top:8px;flex-basis:100%"><a href="#" onclick="toggleEmail(' + a.id + ');return false" style="color:#14632e;font-weight:600;font-size:14px">' + (a.email ? "ইমেইল বদলান" : "ইমেইল বসান") + "</a></div>";
  if (ui.emailFor === a.id) {
    h += '<form onsubmit="return doSetEmail(event,' + a.id + ')" style="margin-top:12px;background:#d9eeda;border-radius:12px;padding:12px;flex-basis:100%">' +
      '<p style="font-weight:600;margin-bottom:6px">' + esc(a.name) + '-এর ইমেইল ঠিকানা</p>' +
      '<p class="dim" style="margin-bottom:10px">অ্যাডমিন অ্যাকাউন্টে ইমেইল থাকা জরুরি — মূল অ্যাডমিনের পাসওয়ার্ড রিসেট এই ইমেইল যাচাই দিয়েই হয়।</p>' +
      '<label><span>ইমেইল ঠিকানা</span><input id="em-set" type="email" required value="' + esc(a.email || "") + '" placeholder="যেমন: name@example.com"></label>' +
      '<div style="display:flex;gap:8px;flex-wrap:wrap"><button type="submit">ইমেইল সংরক্ষণ করুন</button>' +
      '<button type="button" class="ghost" onclick="toggleEmail(' + a.id + ')">বাতিল</button></div></form>';
  }
  return h + "</div></section>";
}
function toggleEmail(id) { ui.emailFor = ui.emailFor === id ? null : id; ui.err = ""; render(); }
function doSetEmail(e, id) {
  e.preventDefault();
  var email = document.getElementById("em-set").value.trim().toLowerCase();
  if (!emailValid(email)) { ui.err = "সঠিক ইমেইল ঠিকানা লিখুন (যেমন: name@example.com)।"; render(); return false; }
  var target = null;
  db.accounts.forEach(function (a) { if (a.id === id) target = a; });
  if (!target) return false;
  target.email = email;
  logReset(target, "অ্যাকাউন্টে ইমেইল বসানো হয়েছে", "ইমেইল " + email + " বসিয়েছেন মূল অ্যাডমিন।");
  ui.emailFor = null;
  save(); ui.err = ""; ui.ok = target.name + "-এর ইমেইল ঠিকানা সংরক্ষণ হয়েছে।"; render();
  return false;
}
function toggleResetPw(id) { ui.resetPwFor = ui.resetPwFor === id ? null : id; ui.err = ""; render(); }
function doAdminResetPw(e, id) {
  e.preventDefault();
  var np = document.getElementById("rp-new").value;
  var target = null;
  db.accounts.forEach(function (a) { if (a.id === id) target = a; });
  if (!target) return false;
  if (target.role === "admin") { ui.err = "অ্যাডমিনের পাসওয়ার্ড সরাসরি এখান থেকে বদলানো যাবে না — অনুমোদনের পথ ব্যবহার করুন (\"যাচাই\" অংশ)।"; render(); return false; }
  target.password = np;
  target.lockUntil = 0;
  delete db.resets[target.phone];
  if (db.sessionId === target.id) db.sessionId = null;
  logReset(target, "মূল অ্যাডমিন সরাসরি দাতার পাসওয়ার্ড রিসেট করেছেন", "রিসেট করেছেন মূল অ্যাডমিন।");
  ui.resetPwFor = null;
  save(); ui.err = ""; ui.ok = target.name + "-এর পাসওয়ার্ড রিসেট হয়েছে — নতুন পাসওয়ার্ডটি তাঁকে জানিয়ে দিন।"; render();
  return false;
}
function setRole(id, role) {
  if (role === "admin") {
    var count = db.accounts.filter(function (a) { return a.role === "admin"; }).length;
    if (count >= MAX_ADMINS) { ui.err = "সর্বোচ্চ " + bn(MAX_ADMINS) + " জন অ্যাডমিন থাকতে পারবেন — আগে কাউকে দাতা করুন বা সরান।"; render(); return; }
  }
  db.accounts.forEach(function (a) { if (a.id === id) a.role = role; });
  save(); ui.err = ""; render();
}
function askRemove(id) { ui.confirmRemove = id; render(); }
function cancelRemove() { ui.confirmRemove = null; render(); }
function removeUser(id) {
  db.accounts = db.accounts.filter(function (a) { return a.id !== id; });
  db.payments = db.payments.filter(function (p) { return p.donorId !== id; });
  delete db.pledges[id];
  ui.confirmRemove = null; save(); render();
}
function doCreateAdmin(e) {
  e.preventDefault();
  var name = document.getElementById("na-name").value.trim();
  var rawPhone = document.getElementById("na-phone").value.trim();
  var phoneErr = mobileNumberError(rawPhone);
  if (phoneErr) { ui.err = phoneErr; render(); return false; }
  var phone = normalizePhoneDigits(rawPhone);
  var email = document.getElementById("na-email").value.trim().toLowerCase();
  if (!emailValid(email)) { ui.err = "সঠিক ইমেইল ঠিকানা লিখুন (যেমন: name@example.com)।"; render(); return false; }
  var pass = document.getElementById("na-pass").value;
  var count = db.accounts.filter(function (a) { return a.role === "admin"; }).length;
  if (count >= MAX_ADMINS) { ui.err = "সর্বোচ্চ " + bn(MAX_ADMINS) + " জন অ্যাডমিন থাকতে পারবেন।"; render(); return false; }
  if (findByPhone(phone)) { ui.err = "এই মোবাইল নম্বর দিয়ে ইতিমধ্যে একটি অ্যাকাউন্ট আছে — চাইলে তালিকা থেকে সেটিকে অ্যাডমিন করুন।"; render(); return false; }
  db.accounts.push({ id: db.nextId++, name: name, phone: phone, email: email, password: pass, address: "", role: "admin", main: false });
  save(); ui.err = ""; ui.ok = "নতুন অ্যাডমিন অ্যাকাউন্ট তৈরি হয়েছে।"; render();
  return false;
}
function doSettings(e) {
  e.preventDefault();
  db.settings.bkash = document.getElementById("st-bkash").value.trim();
  db.settings.nagad = document.getElementById("st-nagad").value.trim();
  db.settings.rocket = document.getElementById("st-rocket").value.trim();
  db.settings.bank = document.getElementById("st-bank").value.trim();
  save(); ui.ok = "পেমেন্ট নম্বর সংরক্ষণ হয়েছে।"; render();
  return false;
}
function doPassword(e) {
  e.preventDefault();
  var u = me();
  if (document.getElementById("pw-cur").value !== u.password) { ui.err = "বর্তমান পাসওয়ার্ড মিলছে না।"; render(); return false; }
  u.password = document.getElementById("pw-new").value;
  save(); ui.err = ""; ui.ok = "পাসওয়ার্ড বদলানো হয়েছে।"; render();
  return false;
}

function doRecoverySettings(e) {
  e.preventDefault();
  var u = me();
  if (!u || !u.main) return false;
  if (document.getElementById("rec-cur").value !== u.password) { ui.err = "বর্তমান পাসওয়ার্ড মিলছে না।"; render(); return false; }
  var email = document.getElementById("rec-email").value.trim();
  var question = document.getElementById("rec-question").value.trim();
  var answer = document.getElementById("rec-answer").value.trim();
  if (!email || !question) { ui.err = "পুনরুদ্ধার ইমেইল ও নিরাপত্তা প্রশ্ন দুটোই লিখুন।"; render(); return false; }
  if (!db.recovery.answer && !answer) { ui.err = "প্রথমবার সেট করার সময় নিরাপত্তা প্রশ্নের উত্তর অবশ্যই দিতে হবে।"; render(); return false; }
  db.recovery.email = email;
  db.recovery.question = question;
  if (answer) db.recovery.answer = answer;
  logReset(u, "মূল অ্যাডমিনের পুনরুদ্ধার তথ্য হালনাগাদ", "পুনরুদ্ধার ইমেইল / নিরাপত্তা প্রশ্ন হালনাগাদ করা হয়েছে।");
  save(); ui.err = ""; ui.ok = "পুনরুদ্ধার তথ্য সংরক্ষণ হয়েছে।"; render();
  return false;
}

/* --------------------------------- মূল render --------------------------------- */
function render() {
  var u = me();
  if (!u) { renderAuth(); return; }
  var html = '<div class="topbar"><span class="brand">শ্রী শ্রী জগন্নাথ মন্দির — দান তহবিল</span>' +
    '<span class="dim">' + esc(u.name) + (u.role === "admin" ? (u.main ? " (মূল অ্যাডমিন)" : " (অ্যাডমিন)") : " (দাতা)") + "</span>";
  if (u.role === "admin") {
    html += '<button type="button" class="pill ' + (ui.view === "admin" ? "on" : "off") + '" onclick="ui.view=\'admin\';render()">অ্যাডমিন প্যানেল</button>' +
      '<button type="button" class="pill ' + (ui.view === "mine" ? "on" : "off") + '" onclick="ui.view=\'mine\';render()">আমার দান</button>';
  }
  html += '<button type="button" class="ghost" onclick="doLogout()">বের হয়ে যান (লগইন পাতায় যান)</button></div><main>';
  html += (u.role === "admin" && ui.view === "admin") ? renderAdmin(u) : renderMine(u);
  html += "</main>";
  document.getElementById("app").innerHTML = html;
}
render();
</script>
</body>
</html>
