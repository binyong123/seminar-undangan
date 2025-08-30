<?php
declare(strict_types=1);
mb_internal_encoding("UTF-8");
date_default_timezone_set('Asia/Jakarta');
session_start();

/* =========================
 *       KONFIGURASI
 * ========================= */
$config = [
  'title'     => 'Puncak Seminar Ilmiah MIPA & TIK Kelas X',
  'tagline'   => 'Transformasi Sains dan Teknologi: Dari Gagasan Menjadi Inovasi',
  'school'    => 'SMA Islam Al-Ma’ruf TP 2025/2026',
  'dates'     => ['2025-09-01','2025-09-02','2025-09-03'], // Senin–Rabu
  'time_start'=> '07:30',
  'time_end'  => '13:00',
  'venue'     => 'GOR Moh Thaha, Jakarta Timur',
  'wa_number' => '6285156202498',
  'theme'     => [
    'bg'     => '#0b3d2e',
    'bg2'    => '#0f5840',
    'card'   => 'rgba(15, 61, 46, 0.75)',
    'text'   => '#e6f2ea',
    'accent' => '#9fe870',
    'muted'  => '#b7d0c2'
  ],
  'agenda' => [
    'Keynote Speech',
    'Presentasi Proyek Ilmiah Siswa',
    'Pameran Produk & Poster STEAM',
    'Apresiasi dan Penghargaan Inovasi'
  ],
  'unggulan' => [
    ['icon' => 'leaf',   'bidang' => 'Biologi',     'judul' => 'Nugget Tempe, Tahu, Sayuran'],
    ['icon' => 'bubbles','bidang' => 'Kimia',       'judul' => 'Sabun dari Ampas Kopi'],
    ['icon' => 'bolt',   'bidang' => 'Fisika',      'judul' => 'Pembangkit Listrik Terbarukan'],
    ['icon' => 'ruler',  'bidang' => 'Matematika',  'judul' => 'Desain Lapangan Basket'],
    ['icon' => 'robot',  'bidang' => 'TIK',         'judul' => 'Aplikasi AI Sederhana'],
  ],
];

/* === DATA KELOMPOK (hardcode, dari dokumen) === */
$kelompok_static = [
  'Kelas Al-Jazari' => [
    1 => ['Abrar Fachri','Raden Neola','Ziovanno','Aryo','Zufar','Dirta','Syifa','Gusti','Zikri','Alif','Allure'],
    2 => ['Rizqo','Hany','Putra','Arfan','Baihaqi','Khaizan','Rafi','Rasya','Hana','Fairuz','Siti Aisyah'],
    3 => ['Carissa','Rizki','Nahdil','Athifa','Dimas','Hilmy','Yandika','Fauzan','Rahman','Athalita'],
  ],
  'Kelas An-Nawawi' => [
    4 => ['Ahmad Ahsan','Dzakwan','Aurelia','Sukainah','Adelia Ayu','Syifa','Zavier','Radityatama','Muhammad Reyhan','Khalila','Ayesha'],
    5 => ['Raden zakhayla','Clianta','Muhammad alrsi','Nahda','Ahmad Syehan','Aryogalih','Kaleena','Ahmad Arsya','Khoirul','Muhammad alveto','Raden zakhayla'],
    6 => ['Naufal','Hadianto','Hassya','Emirsyah','Rafaza zefran','Fikry','Maudina','Irham','Radja','Rafasha','Muhammad azka'],
  ],
  'Kelas Asy-Syatibi' => [
    7 => ['Stevino Farrel','Fredella Lusman','Hafidz Abdurraafi','Alif Abqary','Khirania Gendis Janitra','Dina Saffa Rahmadani',"Yunita Novriyani A\'sing",'Ahmad Zaidan','Saputra','Kayla Nira','Daffaa Athaya'],
    8 => ['Muhammad Devdan Abiya Lukito','Alim Maulana Husain','Audrey Sabian Permana','Naila Valerie Putri','Adelia Shaumy Nafeeza','Pascal Alfathir Wijaya','Sabrina Cut Azzahra','King Saddam El Hessam','Raffa Favian Mahardika','Fiqi Iman Surya Prakoso','Taufiq Al-Hakim'],
    9 => ['Daffa Arizka Akbar','Haura Azizah Putri Ruseno','Irsyad Ibnu Aqil','Raffi Radhitya Fattah','Zeradi Muqsith Hutabarat','Azzahran faza Santoso','Muhammad Dwi Aqiel Caesar','Muhammad Baburrizqy','Aghniza Putri Prihantono','Fahmi Bahtiar'],
  ],
  'Kelas Al-Mawardi' => [
    10 => ['Indah Adzra Rahmadita','Danish Radi Rezsakaputra','Andrew Ahzami Gosiman','Lingga Rafa Nabihan','Muhammad Keenan Athareyn','Rais Fattah Ceyda Elfaisal','Mahamantri Astar De Pralia','Alya Aprilia','Callysta Nabila Cahya','Hanan Sakinah Al Attas','Keenan Lintang Athaya'],
    11 => ['Muhammad Muiz Ramadhany','Pavid Maulud','Alvin Aldiansyah','Syahazlina Ayu Bromantias','Zidane Fahrizal Anas','Darell Alghivari','Izzan Waldan Nitisara','Raka Arsya Athala','Muhammad Dwi Arian','Salwa Nabila Putri'],
    12 => ['Nasyifa Makaila Sahira','Fasahirah Auni Raissa','Fakhru Jaya Samudra','Aisyah Ardhia Soraya','Sarah Aulia Safira','Sutomo Ahmad Jaris','Muhammad Farid Alfarizi','Rio Attalla Asyarif','Althaf Syah Ghiyas','Anisya Syafriyanti'],
  ],
  'Kelas Az-Zahrawi' => [
    13 => ['Keyla','Anaya','Qalesya','Syahmi','Khairi','Gibran','Ravie','Rayi','Dhabit','Kahfi'],
    14 => ['Arina','Fatimah','Aisyah','Galuh','Haydar','Anugrah','Antasena','Rafa','Denzel','Muchlis'],
    15 => ['Marvela','Azarin','Janitra','Ziggy','Farel','Nabil','Raka','Arfa','Wiraga','Prabu'],
  ],
];

/* === JADWAL KELOMPOK (1–3 Sep 2025) — TIK mulai 09.00 dari Kel 14 === */
$jadwal_harian = [
  '2025-09-01' => [
    'judul' => 'Senin, 01 September 2025',
    'labs'  => ['Lab IPA (Kimia)','Lab TIK (Komputer)'],
    'rows'  => [
      ['06.30–07.00',['Pembiasaan Asmaul Husna','Pembiasaan Asmaul Husna']],
      ['07.00–07.30',['Prepare presentasi','Prepare presentasi']],

      ['07.30–07.45',['Kel 1','']],
      ['07.45–08.00',['Kel 2','']],
      ['08.00–08.15',['Kel 3','']],
      ['08.15–08.30',['Kel 4','']],
      ['08.30–08.45',['Kel 5','']],
      ['08.45–09.00',['Kel 6','']],

      ['09.00–09.15',['Kel 7','Kel 14']],
      ['09.15–09.25',['Kel 8','Kel 13']],

      ['09.25–10.00',['Istirahat & Dhuha','Istirahat & Dhuha']],

      ['10.00–10.15',['Kel 9','Kel 1']],
      ['10.15–10.30',['Kel 10','Kel 2']],
      ['10.30–10.45',['Kel 11','Kel 3']],
      ['10.45–11.00',['Kel 12','Kel 4']],
      ['11.00–11.15',['Kel 13','Kel 5']],
      ['11.15–11.30',['Kel 14','Kel 6']],
      ['11.30–11.45',['Kel 15','Kel 7']],
      ['11.45–12.00',['','Kel 8']],
      ['12.00–12.15',['','Kel 9']],
      ['12.15–12.30',['','Kel 10']],
      ['12.30–12.45',['','Kel 11']],
      ['12.45–13.00',['','Kel 12']],
      ['13.00–13.10',['Kel 12','']],

      ['13.10–14.00',['Istirahat & Dzuhur','Istirahat & Dzuhur']],
      ['14.00–14.15',['','Kel 15']],
      ['14.15–15.40',['KBM','KBM']],
    ],
  ],

  '2025-09-02' => [
    'judul' => 'Selasa, 02 September 2025',
    'labs'  => ['Lab IPA (Fisika)','Lab TIK (TIK)'],
    'rows'  => [
      ['06.30–07.00',['Pembiasaan Asmaul Husna','Pembiasaan Asmaul Husna']],
      ['07.00–07.30',['Prepare presentasi','Prepare presentasi']],

      ['07.30–07.45',['Kel 1','']],
      ['07.45–08.00',['Kel 2','']],
      ['08.00–08.15',['Kel 3','']],
      ['08.15–08.30',['Kel 4','']],
      ['08.30–08.45',['Kel 5','']],
      ['08.45–09.00',['Kel 6','']],

      ['09.00–09.15',['Kel 7','Kel 14']],
      ['09.15–09.25',['Kel 8','Kel 13']],

      ['09.25–10.00',['Istirahat & Dhuha','Istirahat & Dhuha']],

      ['10.00–10.15',['Kel 9','Kel 1']],
      ['10.15–10.30',['Kel 10','Kel 2']],
      ['10.30–10.45',['Kel 11','Kel 3']],
      ['10.45–11.00',['Kel 12','Kel 4']],
      ['11.00–11.15',['Kel 13','Kel 5']],
      ['11.15–11.30',['Kel 14','Kel 6']],
      ['11.30–11.45',['Kel 15','Kel 7']],
      ['11.45–12.00',['','Kel 8']],
      ['12.00–12.15',['','Kel 9']],
      ['12.15–12.30',['','Kel 10']],
      ['12.30–12.45',['','Kel 11']],
      ['12.45–13.00',['','Kel 12']],
      ['13.00–13.10',['','Kel 12']],

      ['13.10–14.00',['Istirahat & Dzuhur','Istirahat & Dzuhur']],
      ['14.00–14.15',['','Kel 15']],
      ['14.15–15.40',['KBM','KBM']],
    ],
  ],

  '2025-09-03' => [
    'judul' => 'Rabu, 03 September 2025',
    'labs'  => ['Lab IPA (Biologi)'],
    'rows'  => [
      ['06.30–07.00',['Pembiasaan Asmaul Husna']],
      ['07.00–07.30',['Prepare presentasi']],
      ['07.30–07.45',['Kel 1']],
      ['07.45–08.00',['Kel 2']],
      ['08.00–08.15',['Kel 3']],
      ['08.15–08.30',['Kel 4']],
      ['08.30–08.45',['Kel 5']],
      ['08.45–09.00',['Kel 6']],
      ['09.00–09.15',['Kel 7']],
      ['09.15–09.25',['Kel 8']],
      ['09.25–10.00',['Istirahat & Dhuha']],
      ['10.00–10.15',['Kel 9']],
      ['10.15–10.30',['Kel 10']],
      ['10.30–10.45',['Kel 11']],
      ['10.45–11.00',['Kel 12']],
      ['11.00–11.15',['Kel 13']],
      ['11.15–11.30',['Kel 14']],
      ['11.30–11.45',['Kel 15']],
      ['11.45–12.00',['Closing']],
      ['12.30–15.40',['KBM']],
    ],
  ],
];

/* === Rundown Puncak (8 Sep 2025) === */
$rundown_puncak = [
  'judul' => 'Senin, 08 September 2025 — Puncak Seminar',
  'rows'  => [
    ['06.30–07.00','Pembiasaan Asmaul Husna'],
    ['07.30–08.00','Registrasi'],
    ['08.00–08.15','Sambutan Ketua Pelaksana'],
    ['08.15–08.30','Sambutan & Pembukaan oleh Kepala Sekolah'],
    ['08.30–09.25','Keynote speech'],
    ['09.25–10.30','Istirahat & Dhuha'],
    ['10.30–11.30','Presentasi final'],
    ['11.30–12.15','Pameran poster & produk'],
    ['12.15–12.45','Penilaian juri & voting inovasi terbaik'],
    ['12.45–13.00','Penghargaan & penutupan'],
    ['13.00–15.40','KBM'],
  ],
];

/* ====== Helper ====== */
function esc(string $s): string { return htmlspecialchars($s, ENT_QUOTES, 'UTF-8'); }
function indo_hari(\DateTimeInterface $d): string { $map = ['Minggu','Senin','Selasa','Rabu','Kamis','Jumat','Sabtu']; return $map[(int)$d->format('w')]; }
function indo_bulan(int $m): string { $map = [1=>'Januari','Februari','Maret','April','Mei','Juni','Juli','Agustus','September','Oktober','November','Desember']; return $map[$m] ?? ''; }
function tanggal_range_teks(array $dates): string {
  $first = new DateTime($dates[0]); $last  = new DateTime($dates[count($dates)-1]);
  if ($first->format('mY') === $last->format('mY')) {
    return indo_hari($first).'–'.indo_hari($last).', '.(int)$first->format('j').'–'.(int)$last->format('j').' '.indo_bulan((int)$first->format('n')).' '.$first->format('Y');
  }
  $t1 = (int)$first->format('j').' '.indo_bulan((int)$first->format('n')).' '.$first->format('Y');
  $t2 = (int)$last->format('j').' '.indo_bulan((int)$last->format('n')).' '.$last->format('Y');
  return indo_hari($first).'–'.indo_hari($last).", $t1 – $t2";
}
/* Pewarnaan jadwal */
function schedule_row_class(array $cols): string {
  $t = mb_strtolower(implode(' ', $cols));
  $has = function(string $needle) use ($t){ return stripos($t, $needle) !== false; };
  $cls = [];
  if ($has('asmaul'))                  $cls[]='row-morning';
  if ($has('prepare'))                 $cls[]='row-prepare';
  if ($has('istirahat') || $has('dhuha') || $has('dzuhur') || $has('dzuhr')) $cls[]='row-rest';
  if ($has('closing'))                 $cls[]='row-closing';
  if ($has('kbm'))                     $cls[]='row-kbm';
  if (!$cls && preg_match('/\bkel\b|\bkel\s*\d+/i', $t)) $cls[]='row-kel';
  return implode(' ', $cls);
}

/* ====== State halaman ====== */
$guest = isset($_GET['to']) ? trim(strip_tags($_GET['to'])) : '';
$hariTanggal = tanggal_range_teks($config['dates']);
$is_open = (isset($_GET['open']) && $_GET['open'] === '1');

$mapsQuery = urlencode("SMA ISLAM AL MA'RUF");
$waText = rawurlencode("Assalamu'alaikum, Panitia Seminar MIPA & TIK.");
$waLink = "https://wa.me/{$config['wa_number']}?text=$waText";
$selfUrl = (isset($_SERVER['HTTPS']) && $_SERVER['HTTPS']==='on' ? 'https' : 'http').'://'.$_SERVER['HTTP_HOST'].$_SERVER['REQUEST_URI'];
?>
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title><?=esc($config['title'])?> — <?=esc($config['school'])?></title>
<meta name="description" content="<?=esc($config['tagline'])?> di <?=esc($config['venue'])?>, <?=esc($hariTanggal)?>, pukul <?=esc($config['time_start'])?>–<?=esc($config['time_end'])?> WIB.">
<meta name="theme-color" content="<?=esc($config['theme']['bg'])?>">

<!-- OG -->
<meta property="og:type" content="website">
<meta property="og:title" content="<?=esc($config['title'])?>">
<meta property="og:description" content="<?=esc($config['tagline'])?> — <?=esc($hariTanggal)?> • <?=esc($config['venue'])?>">
<meta property="og:url" content="<?=esc($selfUrl)?>">
<meta name="twitter:card" content="summary_large_image">

<!-- Fonts -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700;800&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">

<!-- Preload logo -->
<link rel="preload" as="image" href="logo.png">

<style>
:root{
  --bg:     <?=$config['theme']['bg']?>;
  --bg2:    <?=$config['theme']['bg2']?>;
  --card:   <?=$config['theme']['card']?>;
  --text:   <?=$config['theme']['text']?>;
  --muted:  <?=$config['theme']['muted']?>;
  --accent: <?=$config['theme']['accent']?>;
  --hl-prepare: rgba(159,232,112,.16);
  --hl-rest:    rgba(255,206,84,.20);
  --hl-morning: rgba(255,255,255,.07);
  --hl-closing: rgba(255,120,120,.22);
  --hl-kbm:     rgba(255,255,255,.05);
  --hl-kel:     rgba(255,255,255,.03);
}
*{box-sizing:border-box}
html,body{height:100%}
body{
  margin:0; font-family: Inter, system-ui, -apple-system, Segoe UI, Roboto, "Helvetica Neue", Arial, "Noto Sans";
  color:var(--text);
  background:
    radial-gradient(1200px 800px at 80% -10%, #16855f22, transparent 70%),
    radial-gradient(900px 600px at -10% 20%, #0a664a33, transparent 70%),
    linear-gradient(145deg, var(--bg), var(--bg2));
  overflow-x:hidden;
}
.container{max-width:1024px; margin:0 auto; padding:24px}

/* ===== COVER ===== */
.cover{ min-height: 70vh; display:flex; flex-direction:column; align-items:center; justify-content:center; text-align:center; padding:56px 12px 24px; }
.cover .label{ display:inline-flex; gap:8px; padding:8px 12px; border-radius:999px; background:rgba(255,255,255,.06); border:1px dashed rgba(255,255,255,.15); margin-bottom:12px; font-size:14px; color:var(--muted)}
/* LOGO */
.cover .logo{
  height:clamp(84px, 12vw, 140px);
  width:auto;
  margin:6px 0 14px;
  display:block;
  filter: drop-shadow(0 8px 20px rgba(0,0,0,.35)) drop-shadow(0 0 18px rgba(159,232,112,.18));
}
.cover .title{ font-family:Poppins,Inter,sans-serif; font-weight:800; letter-spacing:.6px; line-height:1.15; margin:0 0 10px; font-size:clamp(34px,6vw,68px); text-transform:uppercase; }
.cover .subtitle{ color:#def4e7; opacity:.95; font-size:clamp(14px,2.2vw,18px); margin-bottom:16px }
.cover .hint{ margin-top:10px; color:var(--muted); }

/* ===== DETAIL ===== */
.details{ display:none; animation: fadeIn .5s ease both }
body.details-open #details{ display:block }
#details:target{ display:block }
body.details-open #cover{ display:none !important }

@keyframes fadeIn{ from{opacity:0; transform: translateY(6px)} to{opacity:1; transform:none} }
.hero{ display:flex; flex-direction:column; gap:14px; text-align:center; padding:18px 12px 6px; }
.badge{ display:inline-flex; gap:8px; padding:8px 12px; border-radius:999px; background:rgba(255,255,255,.06); border:1px dashed rgba(255,255,255,.15); margin:0 auto 6px; font-size:14px; color:var(--muted)}
h1{ font-family:Poppins,Inter,sans-serif; font-weight:700; margin:0; font-size:clamp(28px,4vw,44px); }
.tagline{ font-size:clamp(15px,2.4vw,20px); color:#def4e7; opacity:.95; margin-top:6px }
.card{ background:var(--card); backdrop-filter:blur(8px); border:1px solid rgba(255,255,255,.08); border-radius:18px; padding:22px; box-shadow:0 10px 30px rgba(0,0,0,.25); }
.grid{ display:grid; gap:18px; grid-template-columns: repeat(12, 1fr); }
.col-6{grid-column:span 6} .col-12{grid-column:span 12}
@media (max-width:800px){ .col-6{grid-column:span 12} }
.section-title{ font-family:Poppins,Inter,sans-serif; font-weight:600; margin:0 0 8px; font-size:20px }
.kv{ display:grid; gap:10px; grid-template-columns:28px 1fr; align-items:start; }
.kv svg{width:22px;height:22px;margin-top:3px}
.kv .k{color:var(--muted); font-size:14px} .kv .v{font-size:16px} .kv strong{font-weight:600}

.agenda{ list-style:none; padding:0; margin:8px 0 0; display:flex; flex-direction:column; gap:8px }
.agenda li{ display:flex; gap:10px; align-items:center; padding:10px 12px; border:1px solid rgba(255,255,255,.08); border-radius:12px; background:rgba(255,255,255,.03) }
.agenda .dot{ width:10px;height:10px;border-radius:50%;background:var(--accent); box-shadow:0 0 0 4px rgba(159,232,112,.18), 0 0 18px rgba(159,232,112,.45) }
.unggulan{ display:grid; gap:12px; grid-template-columns: repeat(5, minmax(0,1fr)) }
@media (max-width:900px){ .unggulan{grid-template-columns: repeat(2, minmax(0,1fr))} }
.unggulan .item{ padding:14px; border-radius:14px; border:1px solid rgba(255,255,255,.09); background:rgba(255,255,255,.03) }
.unggulan .item h4{margin:10px 0 6px; font-size:16px}
.unggulan .item p{margin:0; color:var(--muted); font-size:14px}
.unggulan .icon{width:28px;height:28px}

.cta{ display:flex; flex-wrap:wrap; gap:12px; justify-content:center; margin-top:10px }
.button{ --ring: rgba(159,232,112,.35); display:inline-flex; align-items:center; gap:8px; padding:12px 16px; border-radius:12px; border:1px solid rgba(255,255,255,.10); background:linear-gradient(180deg, rgba(159,232,112,.18), rgba(159,232,112,.12)); color:#053a2a; font-weight:600; text-decoration:none; box-shadow:0 6px 18px rgba(0,0,0,.25), 0 0 0 0 var(--ring); cursor:pointer }
.button:hover{ transform: translateY(-1px); box-shadow:0 10px 28px rgba(0,0,0,.30), 0 0 0 6px var(--ring) }
.button.secondary{ background:rgba(255,255,255,.05); color:var(--text); border-color:rgba(255,255,255,.12) }
.small{font-size:13px;color:var(--muted)}
hr.sep{border:none;height:1px;background:linear-gradient(to right, transparent, rgba(255,255,255,.15), transparent); margin:26px 0}

/* ===== TABEL ===== */
.tbl-wrap{ overflow:auto; -webkit-overflow-scrolling:touch; border-radius:14px; }
.tbl{width:100%; border-collapse:separate; border-spacing:0; min-width:680px}
.tbl th,.tbl td{ padding:10px 12px; border-bottom:1px solid rgba(255,255,255,.08); text-align:left; vertical-align:top; white-space:nowrap }
.tbl thead th{ font-size:13px; color:var(--muted); font-weight:700; letter-spacing:.3px; text-transform:uppercase; background: rgba(255,255,255,.04); position:sticky; top:0; z-index:1 }
.tbl tr:hover td{ background: rgba(255,255,255,.03) }
.badge2{ display:inline-block; padding:4px 8px; border-radius:999px; background: rgba(159,232,112,.12); border:1px solid rgba(159,232,112,.4); color: #e8ffe8; font-size:12px }

/* Pewarnaan khusus jadwal */
.tbl tr.row-prepare td{ background: var(--hl-prepare) }
.tbl tr.row-rest td{ background: var(--hl-rest) }
.tbl tr.row-morning td{ background: var(--hl-morning) }
.tbl tr.row-closing td{ background: var(--hl-closing) }
.tbl tr.row-kbm td{ background: var(--hl-kbm) }
.tbl tr.row-kel:nth-child(odd) td{ background: var(--hl-kel) }

/* Header kolom “Kelompok X” */
.th-group{ background: linear-gradient(180deg, rgba(159,232,112,.18), rgba(159,232,112,.08)) !important; border-bottom-color: rgba(159,232,112,.35) !important }

/* Mobile tweaks */
@media (max-width:640px){
  .tbl th,.tbl td{ padding:8px 10px; font-size:14px }
  .tbl{ min-width:640px }
}

/* Section collapsible */
.section-collapsible{ display:none }
.section-collapsible.is-open{ display:block; animation: fadeIn .45s ease both }
.section-collapsible:target{ display:block; animation: fadeIn .45s ease both }

footer{opacity:.85;text-align:center;padding:22px 0 32px;color:var(--muted);font-size:13px}
blockquote.dua{margin:0;padding:10px 14px;border-left:4px solid var(--accent);background:rgba(255,255,255,.03);border-radius:8px}
</style>
</head>
<body class="<?= $is_open ? 'details-open' : '' ?>">
  <div class="container">

    <!-- ===== COVER ===== -->
    <section id="cover" class="cover">
     
      <!-- LOGO di atas judul -->
      <img class="logo" src="logo.png" alt="Logo Yayasan / SMA Islam Al Ma'ruf" width="280" height="280">
      <h2 class="title">SEMINAR ILMIAH<br>SMA ISLAM AL MA'RUF</h2>
      <div class="subtitle"><?=esc($config['school'])?></div>
      <div class="cta">
        <a id="openInviteBtn" class="button" href="?open=1#details">
          <svg width="18" height="18" viewBox="0 0 24 24" fill="none"><path d="M4 6h16v12H4z" stroke="#0b3d2e" stroke-width="2"/><path d="M4 7l8 6 8-6" stroke="#0b3d2e" stroke-width="2"/></svg>
          UNDANGAN
        </a>
      </div>
      <div class="hint small">Tekan “UNDANGAN” untuk melihat detail acara</div>
    </section>

    <!-- ===== DETAIL ===== -->
    <section id="details" class="details">
      <div class="hero">
        <div class="badge">Assalamu’alaikum warahmatullahi wabarakatuh</div>
        <h1>✨ <?=esc($config['title'])?> ✨</h1>
        <div class="tagline">“<?=esc($config['tagline'])?>”</div>
        <div class="small"><?=esc($config['school'])?></div>

        <div class="cta">
          <a class="button secondary" id="btnKelompok" href="#kelompok">
            <svg width="18" height="18" viewBox="0 0 24 24" fill="none">
              <path d="M16 14c2.2 0 4 1.8 4 4v2H4v-2c0-2.2 1.8-4 4-4" stroke="currentColor" stroke-width="2" stroke-linecap="round"/>
              <circle cx="8" cy="9" r="3" stroke="currentColor" stroke-width="2"/>
              <circle cx="16" cy="9" r="3" stroke="currentColor" stroke-width="2"/>
            </svg>
            DAFTAR KELOMPOK
          </a>
          <a class="button secondary" id="btnJadwal" href="#jadwal">
            <svg width="18" height="18" viewBox="0 0 24 24" fill="none">
              <rect x="3" y="4" width="18" height="18" rx="2" stroke="currentColor" stroke-width="2"/>
              <path d="M16 2v4M8 2v4M3 10h18" stroke="currentColor" stroke-width="2"/>
            </svg>
            JADWAL KELOMPOK
          </a>
          <a class="button secondary" id="btnPuncak" href="#puncak">
            <svg width="18" height="18" viewBox="0 0 24 24" fill="none" aria-hidden="true">
              <path d="M4 20h16M6 20l5-14 3 8 2-5 2 6" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>
            PUNCAK SEMINAR
          </a>

          <a class="button secondary" href="https://www.google.com/maps/search/?api=1&query=<?=$mapsQuery?>" target="_blank" rel="noopener">
            <svg width="18" height="18" viewBox="0 0 24 24" fill="none">
              <path d="M12 22s7-6.1 7-12a7 7 0 10-14 0c0 5.9 7 12 7 12z" stroke="currentColor" stroke-width="2"/>
              <circle cx="12" cy="10" r="3" stroke="currentColor" stroke-width="2"/>
            </svg>
            SMA ISLAM AL MA'RUF
          </a>
          <a class="button secondary" href="<?=$waLink?>" target="_blank" rel="noopener">
            <svg width="18" height="18" viewBox="0 0 24 24" fill="none">
              <path d="M20.5 12a8.5 8.5 0 10-3.1 6.6L21 21l-2.4-3.7A8.4 8.4 0 0020.5 12z" stroke="currentColor" stroke-width="2"/>
              <path d="M8.5 9.5c.5 1.8 2.7 3.8 4.3 4 0 0 .7.1 1.3-.3l.4-.3" stroke="currentColor" stroke-width="2" stroke-linecap="round"/>
            </svg>
            WhatsApp Panitia
          </a>
        </div>
      </div>

      <div class="grid">
        <div class="col-6">
          <div class="card">
            <h3 class="section-title">Detail Acara</h3>
            <div class="kv">
              <svg viewBox="0 0 24 24" fill="none"><rect x="3" y="4" width="18" height="18" rx="2" stroke="currentColor" stroke-width="2"/><path d="M16 2v4M8 2v4M3 10h18" stroke="currentColor" stroke-width="2"/></svg>
              <div><div class="k">Hari/Tanggal</div><div class="v"><strong><?=esc($hariTanggal)?></strong></div></div>
              <svg viewBox="0 0 24 24" fill="none"><path d="M12 8v5l3 2" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><circle cx="12" cy="12" r="9" stroke="currentColor" stroke-width="2"/></svg>
              <div><div class="k">Waktu</div><div class="v"><strong><?=esc($config['time_start'])?> – <?=esc($config['time_end'])?> WIB</strong></div></div>
              <svg viewBox="0 0 24 24" fill="none"><path d="M12 22s7-6.1 7-12a7 7 0 10-14 0c0 5.9 7 12 7 12z" stroke="currentColor" stroke-width="2"/><circle cx="12" cy="10" r="3" stroke="currentColor" stroke-width="2"/></svg>
              <div><div class="k">Tempat</div><div class="v"><strong><?=esc($config['venue'])?></strong></div></div>
            </div>
            <hr class="sep">
            <div class="kv">
              <svg viewBox="0 0 24 24" fill="none"><path d="M4 7h16M4 12h16M4 17h10" stroke="currentColor" stroke-width="2" stroke-linecap="round"/></svg>
              <div>
                <div class="k">Rangkaian Acara</div>
                <ul class="agenda">
                  <?php foreach($config['agenda'] as $a): ?>
                    <li><span class="dot"></span><span><?=esc($a)?></span></li>
                  <?php endforeach; ?>
                </ul>
              </div>
            </div>
          </div>
        </div>

        <div class="col-6">
          <div class="card">
            <h3 class="section-title">Proyek Unggulan Siswa</h3>
            <div class="unggulan">
              <?php
                function iconSvg(string $name): string {
                  if ($name==='leaf') return '<svg class="icon" viewBox="0 0 24 24" fill="none"><path d="M21 3c-8 0-14 6-14 14 0 1 .2 2 .6 3C5 20 2 17 2 12 2 6 8 3 12 3c3.5 0 6.7 1.6 9 4z" stroke="currentColor" stroke-width="2"/><path d="M3 21c6-6 12-10 18-12" stroke="currentColor" stroke-width="2" stroke-linecap="round"/></svg>';
                  if ($name==='bubbles') return '<svg class="icon" viewBox="0 0 24 24" fill="none"><circle cx="7" cy="7" r="3" stroke="currentColor" stroke-width="2"/><circle cx="15" cy="12" r="2" stroke="currentColor" stroke-width="2"/><circle cx="10" cy="17" r="1.8" stroke="currentColor" stroke-width="2"/></svg>';
                  if ($name==='bolt') return '<svg class="icon" viewBox="0 0 24 24" fill="none"><path d="M13 2L3 14h8l-1 8 10-12h-8l1-8z" stroke="currentColor" stroke-width="2" stroke-linejoin="round"/></svg>';
                  if ($name==='ruler') return '<svg class="icon" viewBox="0 0 24 24" fill="none"><rect x="3" y="6" width="18" height="12" rx="2" stroke="currentColor" stroke-width="2"/><path d="M7 10h2M11 10h2M15 10h2M7 14h2M11 14h2M15 14h2" stroke="currentColor" stroke-width="2" stroke-linecap="round"/></svg>';
                  if ($name==='robot') return '<svg class="icon" viewBox="0 0 24 24" fill="none"><rect x="5" y="7" width="14" height="10" rx="2" stroke="currentColor" stroke-width="2"/><circle cx="10" cy="12" r="1.5" stroke="currentColor" stroke-width="2"/><circle cx="14" cy="12" r="1.5" stroke="currentColor" stroke-width="2"/><path d="M12 3v3M5 12H3M21 12h-2M9 19h6" stroke="currentColor" stroke-width="2" stroke-linecap="round"/></svg>';
                  return '';
                }
                foreach($config['unggulan'] as $u):
              ?>
                <div class="item">
                  <?=iconSvg($u['icon'])?>
                  <h4><?=esc($u['bidang'])?></h4>
                  <p><?=esc($u['judul'])?></p>
                </div>
              <?php endforeach; ?>
            </div>
            <hr class="sep">
            <div class="small">📍 Dresscode: <strong>Formal / Batik</strong></div>
            <div class="small">📞 Kontak Panitia: <strong>+<?=esc($config['wa_number'])?></strong></div>
          </div>
        </div>

        <!-- ===== DAFTAR KELOMPOK ===== -->
        <div class="col-12 section-collapsible" id="kelompok">
          <div class="card">
            <h3 class="section-title">Daftar Kelompok</h3>
            <?php
              foreach ($kelompok_static as $kelas => $groups) {
                ksort($groups, SORT_NUMERIC);
                echo '<h4 style="margin:10px 0 8px 0">'.esc($kelas).'</h4>';
                echo '<div class="tbl-wrap"><table class="tbl"><thead><tr>';
                foreach ($groups as $no => $_) { echo '<th class="th-group">Kelompok '.esc((string)$no).'</th>'; }
                echo '</tr></thead><tbody>';
                $max = 0; foreach ($groups as $members) { $max = max($max, count($members)); }
                for ($i=0; $i<$max; $i++) {
                  echo '<tr>';
                  foreach ($groups as $members) { echo '<td>'.esc($members[$i] ?? '').'</td>'; }
                  echo '</tr>';
                }
                echo '</tbody></table></div><hr class="sep">';
              }
            ?>
            <div class="small">Data di-hardcode (tanpa impor Excel). Sumber: dokumen “KELOMPOK PROJECT IPA”.</div>
          </div>
        </div>

        <!-- ===== JADWAL KELOMPOK ===== -->
        <div class="col-12 section-collapsible" id="jadwal">
          <div class="card">
            <h3 class="section-title">Jadwal Kelompok (1–3 September 2025)</h3>
            <?php
              foreach ($jadwal_harian as $info) {
                echo '<h4 style="margin:10px 0 8px 0">'.esc($info['judul']).'</h4>';
                echo '<div class="tbl-wrap"><table class="tbl"><thead><tr><th style="width:140px">Waktu</th>';
                foreach ($info['labs'] as $lab) echo '<th>'.esc($lab).'</th>';
                echo '</tr></thead><tbody>';
                foreach ($info['rows'] as $row) {
                  $waktu = $row[0]; $cols = $row[1]; $cls = schedule_row_class($cols);
                  echo '<tr class="'.esc($cls).'"><td>'.esc($waktu).'</td>';
                  $colCount = count($info['labs']);
                  for ($i=0; $i<$colCount; $i++) { echo '<td>'.esc($cols[$i] ?? '').'</td>'; }
                  echo '</tr>';
                }
                echo '</tbody></table></div><hr class="sep">';
              }
            ?>
          </div>
        </div>

        <!-- ===== RUNDOWN PUNCAK ===== -->
        <div class="col-12 section-collapsible" id="puncak">
          <div class="card">
            <h3 class="section-title">Rundown Puncak Seminar (8 September 2025)</h3>
            <div class="tbl-wrap">
              <table class="tbl">
                <thead><tr><th style="width:140px">Waktu</th><th>Kegiatan</th></tr></thead>
                <tbody>
                  <?php foreach($rundown_puncak['rows'] as $r): ?>
                    <tr class="<?=schedule_row_class([$r[1]])?>"><td><?=esc($r[0])?></td><td><?=esc($r[1])?></td></tr>
                  <?php endforeach; ?>
                </tbody>
              </table>
            </div>
          </div>
        </div>

        <!-- ===== Teks Undangan ===== -->
        <div class="col-12">
          <div class="card">
            <h3 class="section-title">Undangan</h3>
            <p>Assalamu’alaikum warahmatullahi wabarakatuh</p>
            <p>Dengan memohon rahmat dan ridho Allah SWT, kami mengundang Bapak/Ibu <?php if($guest){ echo '<strong>'.esc($guest).'</strong>'; } ?> untuk hadir dalam acara <strong><?=esc($config['title'])?></strong>.</p>
            <blockquote class="dua">Kehadiran Bapak/Ibu menjadi kehormatan dan semangat bagi kami untuk terus berinovasi.</blockquote>
            <p>Wassalamu’alaikum warahmatullahi wabarakatuh</p>
            <p>Hormat kami,<br><strong>Panitia Seminar Ilmiah MIPA & TIK</strong><br><?=esc($config['school'])?></p>
          </div>
        </div>
      </div>

      <footer>
        &copy; <?=date('Y')?> Panitia <?=esc($config['title'])?> • Tema hijau tua — desain modern
      </footer>
    </section>

  </div>

<script>
// ============ JS sederhana & eksklusif ============
(function(){
  var sectionIDs = ['kelompok','jadwal','puncak'];

  function openDetailsIfNeeded() {
    var url = new URL(window.location.href);
    var hash = location.hash.replace('#','');
    if (url.searchParams.get('open') === '1' || hash === 'details' || sectionIDs.indexOf(hash) >= 0) {
      document.body.classList.add('details-open');
      var details = document.getElementById('details');
      if (details) details.classList.add('show');
    }
  }

  function showExclusive(id, updateHash=true){
    sectionIDs.forEach(function(s){
      var el = document.getElementById(s);
      if (!el) return;
      if (s === id) el.classList.add('is-open');
      else el.classList.remove('is-open');
    });
    if (updateHash) location.hash = '#'+id;
    var target = document.getElementById(id);
    if (target) target.scrollIntoView({behavior:'smooth', block:'start'});
  }

  function openFromHash(){
    var id = location.hash.replace('#','');
    if (sectionIDs.indexOf(id) >= 0){
      document.body.classList.add('details-open');
      var details = document.getElementById('details');
      if (details) details.classList.add('show');
      showExclusive(id, /*updateHash=*/false);
    }
  }

  openDetailsIfNeeded();
  openFromHash();
  window.addEventListener('hashchange', openFromHash);

  var openBtn = document.getElementById('openInviteBtn');
  if (openBtn){
    openBtn.addEventListener('click', function(ev){
      ev.preventDefault();
      document.body.classList.add('details-open');
      var details = document.getElementById('details');
      if (details) details.classList.add('show');
      var u = new URL(window.location.href);
      u.searchParams.set('open','1');
      history.replaceState(null,'', u.toString());
      location.hash = '#details';
    });
  }

  var btnKel = document.getElementById('btnKelompok');
  if (btnKel){ btnKel.addEventListener('click', function(e){ e.preventDefault(); showExclusive('kelompok'); }); }

  var btnJad = document.getElementById('btnJadwal');
  if (btnJad){ btnJad.addEventListener('click', function(e){ e.preventDefault(); showExclusive('jadwal'); }); }

  var btnPunc = document.getElementById('btnPuncak');
  if (btnPunc){ btnPunc.addEventListener('click', function(e){ e.preventDefault(); showExclusive('puncak'); }); }
})();
</script>

<!-- Schema.org Event -->
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Event",
  "name": "<?=esc($config['title'])?>",
  "startDate": "<?=$config['dates'][0]?>T<?=str_replace(':','',$config['time_start'])?>:00+07:00",
  "endDate":   "<?=$config['dates'][count($config['dates'])-1]?>T<?=str_replace(':','',$config['time_end'])?>:00+07:00",
  "eventAttendanceMode": "https://schema.org/OfflineEventAttendanceMode",
  "eventStatus": "https://schema.org/EventScheduled",
  "description": "<?=esc($config['tagline'])?>",
  "location": { "@type": "Place", "name": "<?=esc($config['venue'])?>", "address": "<?=esc($config['venue'])?>" },
  "organizer": { "@type": "Organization", "name": "<?=esc($config['school'])?>" }
}
</script>
</body>
</html>
