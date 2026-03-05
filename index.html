<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>APEX ANALYTICS — Intelligence Platform</title>
<link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Syne:wght@400;600;700;800&family=JetBrains+Mono:wght@300;400;500&display=swap" rel="stylesheet">
<style>
  :root {
    --gold: #c9a84c;
    --gold-light: #e8c97a;
    --gold-dim: #7a5f28;
    --bg-void: #020408;
    --bg-dark: #060d16;
    --bg-card: #0a1628;
    --bg-card2: #0d1f38;
    --accent-blue: #1a6bff;
    --accent-cyan: #00d4ff;
    --accent-green: #00ff9d;
    --accent-red: #ff3b5c;
    --text-primary: #e8edf5;
    --text-muted: #4a6080;
    --border: rgba(201,168,76,0.15);
    --border-bright: rgba(201,168,76,0.4);
    --glow-gold: 0 0 40px rgba(201,168,76,0.3);
    --glow-blue: 0 0 40px rgba(26,107,255,0.4);
    --glow-cyan: 0 0 30px rgba(0,212,255,0.3);
  }

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  html { scroll-behavior: smooth; }

  body {
    background: var(--bg-void);
    color: var(--text-primary);
    font-family: 'Syne', sans-serif;
    min-height: 100vh;
    overflow-x: hidden;
    cursor: none;
  }

  /* CUSTOM CURSOR */
  #cursor {
    position: fixed;
    width: 12px; height: 12px;
    background: var(--gold);
    border-radius: 50%;
    pointer-events: none;
    z-index: 9999;
    transform: translate(-50%, -50%);
    transition: transform 0.1s, background 0.2s;
    mix-blend-mode: difference;
  }
  #cursor-ring {
    position: fixed;
    width: 40px; height: 40px;
    border: 1px solid rgba(201,168,76,0.5);
    border-radius: 50%;
    pointer-events: none;
    z-index: 9998;
    transform: translate(-50%, -50%);
    transition: all 0.12s ease-out;
  }

  /* NOISE OVERLAY */
  body::before {
    content: '';
    position: fixed;
    inset: 0;
    background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)' opacity='0.035'/%3E%3C/svg%3E");
    pointer-events: none;
    z-index: 1000;
    opacity: 0.4;
  }

  /* ANIMATED GRID BACKGROUND */
  .grid-bg {
    position: fixed;
    inset: 0;
    background-image:
      linear-gradient(rgba(201,168,76,0.03) 1px, transparent 1px),
      linear-gradient(90deg, rgba(201,168,76,0.03) 1px, transparent 1px);
    background-size: 60px 60px;
    animation: gridShift 20s linear infinite;
  }
  @keyframes gridShift {
    0% { transform: translate(0,0); }
    100% { transform: translate(60px, 60px); }
  }

  /* AMBIENT ORBS */
  .orb {
    position: fixed;
    border-radius: 50%;
    filter: blur(120px);
    pointer-events: none;
    animation: orbFloat 8s ease-in-out infinite alternate;
  }
  .orb-1 { width: 600px; height: 600px; background: rgba(26,107,255,0.08); top: -200px; right: -100px; animation-delay: 0s; }
  .orb-2 { width: 400px; height: 400px; background: rgba(201,168,76,0.07); bottom: -100px; left: -100px; animation-delay: -3s; }
  .orb-3 { width: 300px; height: 300px; background: rgba(0,212,255,0.05); top: 40%; left: 30%; animation-delay: -5s; }
  @keyframes orbFloat {
    0% { transform: translate(0,0) scale(1); }
    100% { transform: translate(30px, -30px) scale(1.1); }
  }

  /* LAYOUT */
  .shell {
    position: relative;
    z-index: 10;
    max-width: 1600px;
    margin: 0 auto;
    padding: 0 32px 60px;
  }

  /* TOP BAR */
  .topbar {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 28px 0 32px;
    border-bottom: 1px solid var(--border);
    animation: slideDown 0.8s cubic-bezier(0.16,1,0.3,1) both;
  }
  @keyframes slideDown {
    from { opacity: 0; transform: translateY(-20px); }
    to { opacity: 1; transform: translateY(0); }
  }

  .logo {
    display: flex;
    align-items: baseline;
    gap: 12px;
  }
  .logo-mark {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 36px;
    letter-spacing: 4px;
    background: linear-gradient(135deg, var(--gold-light), var(--gold), var(--gold-dim));
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    filter: drop-shadow(0 0 20px rgba(201,168,76,0.4));
  }
  .logo-sub {
    font-family: 'JetBrains Mono', monospace;
    font-size: 10px;
    color: var(--text-muted);
    letter-spacing: 3px;
    text-transform: uppercase;
    border-left: 1px solid var(--border-bright);
    padding-left: 12px;
  }

  .topbar-right {
    display: flex;
    align-items: center;
    gap: 24px;
  }
  .live-badge {
    display: flex;
    align-items: center;
    gap: 8px;
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    color: var(--accent-green);
    letter-spacing: 2px;
  }
  .live-dot {
    width: 8px; height: 8px;
    background: var(--accent-green);
    border-radius: 50%;
    box-shadow: 0 0 10px var(--accent-green);
    animation: livePulse 1.5s ease-in-out infinite;
  }
  @keyframes livePulse {
    0%, 100% { opacity: 1; transform: scale(1); }
    50% { opacity: 0.4; transform: scale(0.7); }
  }

  .time-display {
    font-family: 'JetBrains Mono', monospace;
    font-size: 14px;
    color: var(--text-muted);
  }

  /* HERO SECTION */
  .hero {
    padding: 60px 0 40px;
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 60px;
    align-items: center;
    animation: fadeUp 0.9s cubic-bezier(0.16,1,0.3,1) 0.2s both;
  }
  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(30px); }
    to { opacity: 1; transform: translateY(0); }
  }

  .hero-title {
    font-family: 'Bebas Neue', sans-serif;
    font-size: clamp(48px, 6vw, 88px);
    line-height: 0.95;
    letter-spacing: 2px;
    color: var(--text-primary);
  }
  .hero-title span {
    background: linear-gradient(90deg, var(--gold-light), var(--accent-cyan));
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
  }

  .hero-meta {
    font-family: 'JetBrains Mono', monospace;
    font-size: 12px;
    color: var(--text-muted);
    letter-spacing: 2px;
    margin-top: 16px;
    text-transform: uppercase;
  }

  /* MAIN KPI STRIP */
  .kpi-strip {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 2px;
    margin-bottom: 32px;
    animation: fadeUp 0.9s cubic-bezier(0.16,1,0.3,1) 0.35s both;
  }

  .kpi-card {
    background: var(--bg-card);
    border: 1px solid var(--border);
    padding: 28px 24px;
    position: relative;
    overflow: hidden;
    transition: all 0.4s cubic-bezier(0.16,1,0.3,1);
    cursor: pointer;
  }
  .kpi-card::before {
    content: '';
    position: absolute;
    top: 0; left: 0; right: 0;
    height: 2px;
    background: linear-gradient(90deg, transparent, var(--kpi-color, var(--gold)), transparent);
    opacity: 0;
    transition: opacity 0.3s;
  }
  .kpi-card::after {
    content: '';
    position: absolute;
    inset: 0;
    background: radial-gradient(circle at 50% 0%, rgba(201,168,76,0.05) 0%, transparent 70%);
    opacity: 0;
    transition: opacity 0.4s;
  }
  .kpi-card:hover { transform: translateY(-4px); border-color: var(--border-bright); box-shadow: var(--glow-gold); }
  .kpi-card:hover::before { opacity: 1; }
  .kpi-card:hover::after { opacity: 1; }

  .kpi-card:nth-child(1) { --kpi-color: var(--gold); }
  .kpi-card:nth-child(2) { --kpi-color: var(--accent-cyan); }
  .kpi-card:nth-child(3) { --kpi-color: var(--accent-green); }
  .kpi-card:nth-child(4) { --kpi-color: var(--accent-red); }

  .kpi-label {
    font-family: 'JetBrains Mono', monospace;
    font-size: 10px;
    color: var(--text-muted);
    letter-spacing: 3px;
    text-transform: uppercase;
    margin-bottom: 12px;
  }
  .kpi-value {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 48px;
    line-height: 1;
    letter-spacing: 2px;
    color: var(--kpi-color, var(--gold));
    filter: drop-shadow(0 0 20px currentColor);
    transition: all 0.3s;
  }
  .kpi-change {
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    margin-top: 8px;
    display: flex;
    align-items: center;
    gap: 4px;
  }
  .kpi-change.up { color: var(--accent-green); }
  .kpi-change.down { color: var(--accent-red); }

  /* CHART AREA */
  .dashboard-grid {
    display: grid;
    grid-template-columns: 2fr 1fr;
    gap: 2px;
    margin-bottom: 2px;
    animation: fadeUp 0.9s cubic-bezier(0.16,1,0.3,1) 0.5s both;
  }

  .panel {
    background: var(--bg-card);
    border: 1px solid var(--border);
    padding: 28px;
    position: relative;
    overflow: hidden;
  }
  .panel::before {
    content: '';
    position: absolute;
    top: -50%; left: -50%;
    width: 200%; height: 200%;
    background: conic-gradient(from 0deg at 50% 50%, transparent 340deg, rgba(201,168,76,0.03) 360deg);
    animation: panelRotate 12s linear infinite;
  }
  @keyframes panelRotate {
    from { transform: rotate(0deg); }
    to { transform: rotate(360deg); }
  }

  .panel-inner { position: relative; z-index: 1; }

  .panel-header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 24px;
  }
  .panel-title {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 20px;
    letter-spacing: 3px;
    color: var(--text-primary);
  }
  .panel-badge {
    font-family: 'JetBrains Mono', monospace;
    font-size: 10px;
    padding: 4px 10px;
    border: 1px solid var(--border-bright);
    color: var(--gold);
    letter-spacing: 2px;
  }

  /* SVG CHARTS */
  .chart-container { width: 100%; }

  .chart-svg { width: 100%; overflow: visible; }

  /* LINE CHART */
  .line-path {
    fill: none;
    stroke: var(--gold);
    stroke-width: 2.5;
    stroke-linecap: round;
    stroke-linejoin: round;
    filter: drop-shadow(0 0 8px rgba(201,168,76,0.6));
    stroke-dasharray: 1000;
    stroke-dashoffset: 1000;
    animation: drawLine 2.5s cubic-bezier(0.4,0,0.2,1) 0.8s forwards;
  }
  .line-path-2 {
    fill: none;
    stroke: var(--accent-cyan);
    stroke-width: 2;
    stroke-linecap: round;
    stroke-linejoin: round;
    filter: drop-shadow(0 0 8px rgba(0,212,255,0.5));
    stroke-dasharray: 1000;
    stroke-dashoffset: 1000;
    animation: drawLine 2.5s cubic-bezier(0.4,0,0.2,1) 1.1s forwards;
  }
  @keyframes drawLine {
    to { stroke-dashoffset: 0; }
  }

  .area-fill {
    fill: url(#areaGrad);
    opacity: 0;
    animation: areaFadeIn 1s ease 2s forwards;
  }
  @keyframes areaFadeIn {
    to { opacity: 1; }
  }

  .chart-dot {
    fill: var(--gold);
    r: 4;
    filter: drop-shadow(0 0 6px rgba(201,168,76,0.8));
    opacity: 0;
    animation: dotPop 0.3s ease forwards;
  }
  .chart-dot:nth-child(1) { animation-delay: 2.8s; }
  .chart-dot:nth-child(2) { animation-delay: 2.9s; }
  .chart-dot:nth-child(3) { animation-delay: 3.0s; }
  .chart-dot:nth-child(4) { animation-delay: 3.1s; }
  .chart-dot:nth-child(5) { animation-delay: 3.2s; }
  .chart-dot:nth-child(6) { animation-delay: 3.3s; }
  .chart-dot:nth-child(7) { animation-delay: 3.4s; }
  @keyframes dotPop {
    from { opacity: 0; transform: scale(0); transform-box: fill-box; transform-origin: center; }
    60% { opacity: 1; transform: scale(1.5); }
    to { opacity: 1; transform: scale(1); }
  }

  .chart-axis-text {
    fill: var(--text-muted);
    font-family: 'JetBrains Mono', monospace;
    font-size: 10px;
  }
  .chart-gridline {
    stroke: rgba(201,168,76,0.05);
    stroke-width: 1;
  }

  /* BAR CHART */
  .bar-rect {
    rx: 2;
    transform-box: fill-box;
    transform-origin: bottom;
    transform: scaleY(0);
    animation: barGrow 0.8s cubic-bezier(0.34,1.56,0.64,1) forwards;
  }
  .bar-rect:nth-child(1) { animation-delay: 0.6s; }
  .bar-rect:nth-child(2) { animation-delay: 0.7s; }
  .bar-rect:nth-child(3) { animation-delay: 0.8s; }
  .bar-rect:nth-child(4) { animation-delay: 0.9s; }
  .bar-rect:nth-child(5) { animation-delay: 1.0s; }
  .bar-rect:nth-child(6) { animation-delay: 1.1s; }
  @keyframes barGrow {
    to { transform: scaleY(1); }
  }

  /* DONUT CHART */
  .donut-ring {
    fill: none;
    stroke-width: 16;
    stroke-linecap: round;
    transform-origin: center;
    transform: rotate(-90deg);
    stroke-dasharray: 0 251;
    animation: donutFill 1.5s cubic-bezier(0.4,0,0.2,1) forwards;
  }
  .donut-ring-1 { stroke: var(--gold); animation-delay: 0.5s; }
  .donut-ring-2 { stroke: var(--accent-cyan); animation-delay: 0.7s; }
  .donut-ring-3 { stroke: var(--accent-green); animation-delay: 0.9s; }
  @keyframes donutFill {
    from { stroke-dasharray: 0 251; }
  }

  .donut-center-val {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 32px;
    fill: var(--text-primary);
    text-anchor: middle;
    dominant-baseline: middle;
  }
  .donut-center-label {
    font-family: 'JetBrains Mono', monospace;
    font-size: 9px;
    fill: var(--text-muted);
    text-anchor: middle;
    letter-spacing: 2px;
  }

  /* BOTTOM ROW */
  .bottom-row {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    gap: 2px;
    animation: fadeUp 0.9s cubic-bezier(0.16,1,0.3,1) 0.65s both;
  }

  /* RADIAL GAUGE */
  .gauge-arc-bg {
    fill: none;
    stroke: rgba(255,255,255,0.04);
    stroke-width: 14;
    stroke-linecap: round;
  }
  .gauge-arc {
    fill: none;
    stroke-width: 14;
    stroke-linecap: round;
    transform-origin: center;
    transform: rotate(-220deg);
    stroke-dasharray: 0 300;
    animation: gaugeFill 2s cubic-bezier(0.4,0,0.2,1) 0.5s forwards;
    filter: drop-shadow(0 0 8px currentColor);
  }
  @keyframes gaugeFill {
    from { stroke-dasharray: 0 300; }
  }

  /* HEATMAP */
  .heatmap-grid {
    display: grid;
    grid-template-columns: repeat(12, 1fr);
    gap: 3px;
    margin-top: 12px;
  }
  .hm-cell {
    aspect-ratio: 1;
    border-radius: 2px;
    opacity: 0;
    animation: cellFade 0.2s ease forwards;
    transition: transform 0.2s, filter 0.2s;
  }
  .hm-cell:hover { transform: scale(1.3); filter: brightness(1.5); }

  /* SCROLLING TICKER */
  .ticker-wrap {
    width: 100%;
    overflow: hidden;
    border-top: 1px solid var(--border);
    border-bottom: 1px solid var(--border);
    padding: 10px 0;
    margin: 32px 0;
    background: rgba(201,168,76,0.02);
    animation: fadeUp 0.9s cubic-bezier(0.16,1,0.3,1) 0.8s both;
  }
  .ticker-inner {
    display: flex;
    gap: 60px;
    animation: ticker 25s linear infinite;
    width: max-content;
  }
  @keyframes ticker {
    from { transform: translateX(0); }
    to { transform: translateX(-50%); }
  }
  .ticker-item {
    display: flex;
    align-items: center;
    gap: 12px;
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    white-space: nowrap;
    color: var(--text-muted);
  }
  .ticker-item strong { color: var(--text-primary); }
  .ticker-item .up { color: var(--accent-green); }
  .ticker-item .dn { color: var(--accent-red); }

  /* SPARKLINES */
  .sparkline {
    stroke-width: 1.5;
    fill: none;
    stroke-dasharray: 200;
    stroke-dashoffset: 200;
    animation: drawLine 1.5s ease forwards;
  }

  /* PROGRESS BARS */
  .progress-list { display: flex; flex-direction: column; gap: 16px; }
  .progress-item {}
  .progress-meta {
    display: flex;
    justify-content: space-between;
    margin-bottom: 6px;
    font-size: 12px;
  }
  .progress-name { color: var(--text-primary); font-weight: 600; }
  .progress-pct { font-family: 'JetBrains Mono', monospace; color: var(--text-muted); }
  .progress-track {
    height: 3px;
    background: rgba(255,255,255,0.06);
    border-radius: 2px;
    overflow: hidden;
  }
  .progress-fill {
    height: 100%;
    border-radius: 2px;
    transform: scaleX(0);
    transform-origin: left;
    animation: fillBar 1.2s cubic-bezier(0.4,0,0.2,1) forwards;
  }
  .progress-item:nth-child(1) .progress-fill { animation-delay: 0.8s; }
  .progress-item:nth-child(2) .progress-fill { animation-delay: 0.95s; }
  .progress-item:nth-child(3) .progress-fill { animation-delay: 1.1s; }
  .progress-item:nth-child(4) .progress-fill { animation-delay: 1.25s; }
  .progress-item:nth-child(5) .progress-fill { animation-delay: 1.4s; }
  @keyframes fillBar { to { transform: scaleX(1); } }

  /* TABLE */
  .data-table { width: 100%; border-collapse: collapse; }
  .data-table thead th {
    font-family: 'JetBrains Mono', monospace;
    font-size: 9px;
    color: var(--text-muted);
    letter-spacing: 3px;
    text-transform: uppercase;
    padding: 8px 12px;
    text-align: left;
    border-bottom: 1px solid var(--border);
  }
  .data-table tbody tr {
    border-bottom: 1px solid rgba(201,168,76,0.04);
    transition: background 0.2s;
    opacity: 0;
    animation: rowFade 0.4s ease forwards;
  }
  .data-table tbody tr:hover { background: rgba(201,168,76,0.04); }
  .data-table tbody tr:nth-child(1) { animation-delay: 0.9s; }
  .data-table tbody tr:nth-child(2) { animation-delay: 1.0s; }
  .data-table tbody tr:nth-child(3) { animation-delay: 1.1s; }
  .data-table tbody tr:nth-child(4) { animation-delay: 1.2s; }
  .data-table tbody tr:nth-child(5) { animation-delay: 1.3s; }
  @keyframes rowFade {
    from { opacity: 0; transform: translateX(-10px); }
    to { opacity: 1; transform: translateX(0); }
  }
  .data-table tbody td {
    padding: 12px 12px;
    font-size: 13px;
  }
  .data-table .td-mono {
    font-family: 'JetBrains Mono', monospace;
    font-size: 12px;
    color: var(--text-muted);
  }
  .status-dot {
    display: inline-block;
    width: 6px; height: 6px;
    border-radius: 50%;
    margin-right: 6px;
  }

  /* SCAN LINE EFFECT */
  @keyframes scan {
    0% { top: -100%; }
    100% { top: 200%; }
  }
  .scan-line {
    position: fixed;
    left: 0; right: 0;
    height: 2px;
    background: linear-gradient(90deg, transparent, rgba(201,168,76,0.06), transparent);
    animation: scan 8s linear infinite;
    pointer-events: none;
    z-index: 999;
  }

  /* NUMBER COUNTER ANIMATION */
  .count-up {
    display: inline-block;
  }

  /* GLITCH TEXT */
  .glitch {
    position: relative;
  }
  .glitch::before, .glitch::after {
    content: attr(data-text);
    position: absolute;
    top: 0; left: 0;
    width: 100%; height: 100%;
  }
  .glitch::before {
    color: var(--accent-cyan);
    clip-path: polygon(0 30%, 100% 30%, 100% 50%, 0 50%);
    transform: translateX(-2px);
    animation: glitch1 4s infinite;
  }
  .glitch::after {
    color: var(--accent-red);
    clip-path: polygon(0 60%, 100% 60%, 100% 70%, 0 70%);
    transform: translateX(2px);
    animation: glitch2 4s infinite;
  }
  @keyframes glitch1 {
    0%, 94%, 100% { transform: translateX(0); opacity: 0; }
    95% { transform: translateX(-3px); opacity: 0.8; }
    97% { transform: translateX(3px); opacity: 0.8; }
  }
  @keyframes glitch2 {
    0%, 93%, 100% { transform: translateX(0); opacity: 0; }
    94% { transform: translateX(3px); opacity: 0.8; }
    96% { transform: translateX(-3px); opacity: 0.8; }
  }

  /* CINEMATIC LOADING INTRO */
  #intro {
    position: fixed;
    inset: 0;
    background: var(--bg-void);
    z-index: 9999;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    gap: 24px;
    animation: introOut 0.6s ease 2.5s forwards;
  }
  @keyframes introOut {
    to { opacity: 0; pointer-events: none; }
  }
  .intro-logo {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 72px;
    letter-spacing: 16px;
    background: linear-gradient(135deg, var(--gold-light), var(--gold), var(--gold-dim));
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    animation: introPulse 2s ease infinite;
  }
  @keyframes introPulse {
    0%, 100% { filter: drop-shadow(0 0 20px rgba(201,168,76,0.3)); }
    50% { filter: drop-shadow(0 0 60px rgba(201,168,76,0.7)); }
  }
  .intro-bar-wrap {
    width: 300px;
    height: 2px;
    background: rgba(255,255,255,0.06);
    border-radius: 1px;
    overflow: hidden;
  }
  .intro-bar-fill {
    height: 100%;
    background: linear-gradient(90deg, var(--gold-dim), var(--gold-light));
    border-radius: 1px;
    box-shadow: 0 0 20px var(--gold);
    animation: introLoad 2.2s ease forwards;
  }
  @keyframes introLoad {
    from { width: 0%; }
    to { width: 100%; }
  }
  .intro-text {
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    color: var(--text-muted);
    letter-spacing: 4px;
    animation: introTextBlink 0.5s linear infinite;
  }
  @keyframes introTextBlink {
    0%, 100% { opacity: 1; }
    50% { opacity: 0.3; }
  }

  /* SEPARATOR */
  .sep {
    height: 1px;
    background: linear-gradient(90deg, transparent, var(--border-bright), transparent);
    margin: 2px 0;
  }

  @media (max-width: 1100px) {
    .kpi-strip { grid-template-columns: repeat(2, 1fr); }
    .dashboard-grid { grid-template-columns: 1fr; }
    .bottom-row { grid-template-columns: 1fr; }
    .hero { grid-template-columns: 1fr; }
  }
</style>
</head>
<body>

<!-- CINEMATIC INTRO -->
<div id="intro">
  <div class="intro-logo glitch" data-text="APEX">APEX</div>
  <div class="intro-bar-wrap">
    <div class="intro-bar-fill"></div>
  </div>
  <div class="intro-text">INITIALIZING INTELLIGENCE PLATFORM...</div>
</div>

<!-- SCAN LINE -->
<div class="scan-line"></div>

<!-- CUSTOM CURSOR -->
<div id="cursor"></div>
<div id="cursor-ring"></div>

<!-- AMBIENT -->
<div class="grid-bg"></div>
<div class="orb orb-1"></div>
<div class="orb orb-2"></div>
<div class="orb orb-3"></div>

<div class="shell">

  <!-- TOP BAR -->
  <header class="topbar">
    <div class="logo">
      <div class="logo-mark">APEX</div>
      <div class="logo-sub">Analytics Intelligence Platform</div>
    </div>
    <div class="topbar-right">
      <div class="live-badge">
        <div class="live-dot"></div>
        LIVE
      </div>
      <div class="time-display" id="clock">--:--:--</div>
    </div>
  </header>

  <!-- TICKER -->
  <div class="ticker-wrap">
    <div class="ticker-inner" id="ticker"></div>
  </div>

  <!-- HERO -->
  <section class="hero">
    <div>
      <div class="hero-title glitch" data-text="REVENUE">
        REVENUE<br><span>INTELLIGENCE</span>
      </div>
      <div class="hero-meta">Q4 2024 &nbsp;·&nbsp; GLOBAL CONSOLIDATED &nbsp;·&nbsp; UPDATED 00:00:00</div>
    </div>
    <div>
      <!-- MINI SPARKLINE HERO CHART -->
      <svg viewBox="0 0 400 120" class="chart-svg">
        <defs>
          <linearGradient id="heroGrad" x1="0" y1="0" x2="0" y2="1">
            <stop offset="0%" stop-color="rgba(201,168,76,0.3)"/>
            <stop offset="100%" stop-color="rgba(201,168,76,0)"/>
          </linearGradient>
        </defs>
        <path d="M0,100 C30,90 60,70 90,60 C120,50 150,55 180,40 C210,25 240,30 270,20 C300,10 330,15 360,8 L400,5" class="line-path" style="stroke:var(--gold)"/>
        <path d="M0,100 C30,90 60,70 90,60 C120,50 150,55 180,40 C210,25 240,30 270,20 C300,10 330,15 360,8 L400,5 L400,120 L0,120 Z" fill="url(#heroGrad)" class="area-fill"/>
        <text x="0" y="115" class="chart-axis-text">JAN</text>
        <text x="90" y="115" class="chart-axis-text">MAR</text>
        <text x="180" y="115" class="chart-axis-text">JUN</text>
        <text x="270" y="115" class="chart-axis-text">SEP</text>
        <text x="355" y="115" class="chart-axis-text">DEC</text>
      </svg>
    </div>
  </section>

  <!-- KPI STRIP -->
  <section class="kpi-strip">
    <div class="kpi-card">
      <div class="kpi-label">Total Revenue</div>
      <div class="kpi-value" id="kpi1">$0</div>
      <div class="kpi-change up">▲ 23.4% vs last quarter</div>
    </div>
    <div class="kpi-card">
      <div class="kpi-label">Active Users</div>
      <div class="kpi-value" id="kpi2">0</div>
      <div class="kpi-change up">▲ 8.7% week over week</div>
    </div>
    <div class="kpi-card">
      <div class="kpi-label">Conversion Rate</div>
      <div class="kpi-value" id="kpi3">0%</div>
      <div class="kpi-change up">▲ 1.2pp improvement</div>
    </div>
    <div class="kpi-card">
      <div class="kpi-label">Churn Risk</div>
      <div class="kpi-value" id="kpi4">0%</div>
      <div class="kpi-change down">▼ 0.8pp reduction</div>
    </div>
  </section>

  <!-- MAIN CHARTS -->
  <div class="dashboard-grid">
    <!-- LINE CHART -->
    <div class="panel">
      <div class="panel-inner">
        <div class="panel-header">
          <div class="panel-title">Monthly Performance Trend</div>
          <div class="panel-badge">REVENUE vs TARGET</div>
        </div>
        <div class="chart-container">
          <svg viewBox="0 0 700 220" class="chart-svg">
            <defs>
              <linearGradient id="areaGrad" x1="0" y1="0" x2="0" y2="1">
                <stop offset="0%" stop-color="rgba(201,168,76,0.25)"/>
                <stop offset="100%" stop-color="rgba(201,168,76,0)"/>
              </linearGradient>
              <linearGradient id="areaGrad2" x1="0" y1="0" x2="0" y2="1">
                <stop offset="0%" stop-color="rgba(0,212,255,0.15)"/>
                <stop offset="100%" stop-color="rgba(0,212,255,0)"/>
              </linearGradient>
            </defs>
            <!-- Grid lines -->
            <line x1="60" y1="20" x2="680" y2="20" class="chart-gridline"/>
            <line x1="60" y1="60" x2="680" y2="60" class="chart-gridline"/>
            <line x1="60" y1="100" x2="680" y2="100" class="chart-gridline"/>
            <line x1="60" y1="140" x2="680" y2="140" class="chart-gridline"/>
            <line x1="60" y1="180" x2="680" y2="180" class="chart-gridline"/>
            <!-- Y axis labels -->
            <text x="50" y="24" class="chart-axis-text" text-anchor="end">120M</text>
            <text x="50" y="64" class="chart-axis-text" text-anchor="end">90M</text>
            <text x="50" y="104" class="chart-axis-text" text-anchor="end">60M</text>
            <text x="50" y="144" class="chart-axis-text" text-anchor="end">30M</text>
            <text x="50" y="184" class="chart-axis-text" text-anchor="end">0</text>
            <!-- X axis labels -->
            <text x="90" y="205" class="chart-axis-text" text-anchor="middle">Jan</text>
            <text x="182" y="205" class="chart-axis-text" text-anchor="middle">Feb</text>
            <text x="274" y="205" class="chart-axis-text" text-anchor="middle">Mar</text>
            <text x="366" y="205" class="chart-axis-text" text-anchor="middle">Apr</text>
            <text x="458" y="205" class="chart-axis-text" text-anchor="middle">May</text>
            <text x="550" y="205" class="chart-axis-text" text-anchor="middle">Jun</text>
            <text x="642" y="205" class="chart-axis-text" text-anchor="middle">Jul</text>
            <!-- Area fill -->
            <path d="M90,150 C115,140 140,120 182,100 C210,85 240,90 274,70 C310,50 340,55 366,35 C400,15 430,22 458,28 C490,34 520,28 550,22 L642,18 L642,180 L90,180 Z" class="area-fill"/>
            <!-- Target line (dashed) -->
            <path d="M90,130 C182,120 274,100 366,80 C458,60 550,50 642,40" fill="none" stroke="rgba(0,212,255,0.4)" stroke-width="1.5" stroke-dasharray="6,4" class="line-path-2"/>
            <!-- Main line -->
            <path d="M90,150 C115,140 140,120 182,100 C210,85 240,90 274,70 C310,50 340,55 366,35 C400,15 430,22 458,28 C490,34 520,28 550,22 L642,18" class="line-path"/>
            <!-- Data dots -->
            <circle class="chart-dot" cx="90" cy="150"/>
            <circle class="chart-dot" cx="182" cy="100"/>
            <circle class="chart-dot" cx="274" cy="70"/>
            <circle class="chart-dot" cx="366" cy="35"/>
            <circle class="chart-dot" cx="458" cy="28"/>
            <circle class="chart-dot" cx="550" cy="22"/>
            <circle class="chart-dot" cx="642" cy="18"/>
          </svg>
        </div>
      </div>
    </div>

    <!-- DONUT CHART -->
    <div class="panel">
      <div class="panel-inner">
        <div class="panel-header">
          <div class="panel-title">Revenue Mix</div>
          <div class="panel-badge">Q4 2024</div>
        </div>
        <div style="display:flex;justify-content:center;">
          <svg viewBox="0 0 200 200" width="180" height="180">
            <circle cx="100" cy="100" r="70" fill="none" stroke="rgba(255,255,255,0.04)" stroke-width="16"/>
            <!-- Segments using stroke-dasharray trick -->
            <circle class="donut-ring donut-ring-1" cx="100" cy="100" r="40" style="stroke-dasharray: 100 151;"/>
            <circle class="donut-ring donut-ring-2" cx="100" cy="100" r="56" style="stroke-dasharray: 75 276; transform: rotate(calc(-90deg + 143deg));"/>
            <circle class="donut-ring donut-ring-3" cx="100" cy="100" r="72" style="stroke-dasharray: 50 402; transform: rotate(calc(-90deg + 251deg));"/>
            <text x="100" y="97" class="donut-center-val">$84M</text>
            <text x="100" y="113" class="donut-center-label">TOTAL</text>
          </svg>
        </div>
        <div class="progress-list" style="margin-top:16px;">
          <div style="display:flex;justify-content:space-between;align-items:center;font-size:12px;">
            <span style="display:flex;align-items:center;gap:8px;"><span style="width:8px;height:8px;background:var(--gold);border-radius:2px;display:inline-block;"></span>Enterprise</span>
            <span style="font-family:JetBrains Mono,monospace;color:var(--text-muted);">$44.7M — 53%</span>
          </div>
          <div style="display:flex;justify-content:space-between;align-items:center;font-size:12px;margin-top:8px;">
            <span style="display:flex;align-items:center;gap:8px;"><span style="width:8px;height:8px;background:var(--accent-cyan);border-radius:2px;display:inline-block;"></span>Mid-Market</span>
            <span style="font-family:JetBrains Mono,monospace;color:var(--text-muted);">$25.2M — 30%</span>
          </div>
          <div style="display:flex;justify-content:space-between;align-items:center;font-size:12px;margin-top:8px;">
            <span style="display:flex;align-items:center;gap:8px;"><span style="width:8px;height:8px;background:var(--accent-green);border-radius:2px;display:inline-block;"></span>SMB</span>
            <span style="font-family:JetBrains Mono,monospace;color:var(--text-muted);">$14.1M — 17%</span>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="sep"></div>

  <!-- BOTTOM ROW -->
  <div class="bottom-row">

    <!-- BAR CHART -->
    <div class="panel">
      <div class="panel-inner">
        <div class="panel-header">
          <div class="panel-title">Regional Breakdown</div>
          <div class="panel-badge">YTD</div>
        </div>
        <svg viewBox="0 0 280 180" class="chart-svg">
          <defs>
            <linearGradient id="barGrad" x1="0" y1="0" x2="0" y2="1">
              <stop offset="0%" stop-color="var(--gold-light)"/>
              <stop offset="100%" stop-color="var(--gold-dim)"/>
            </linearGradient>
          </defs>
          <rect class="bar-rect" x="10" y="30" width="30" height="130" fill="url(#barGrad)" opacity="0.9"/>
          <rect class="bar-rect" x="55" y="60" width="30" height="100" fill="url(#barGrad)" opacity="0.8"/>
          <rect class="bar-rect" x="100" y="50" width="30" height="110" fill="url(#barGrad)" opacity="0.7"/>
          <rect class="bar-rect" x="145" y="80" width="30" height="80" fill="url(#barGrad)" opacity="0.6"/>
          <rect class="bar-rect" x="190" y="100" width="30" height="60" fill="url(#barGrad)" opacity="0.5"/>
          <rect class="bar-rect" x="235" y="120" width="30" height="40" fill="url(#barGrad)" opacity="0.4"/>
          <text x="25" y="175" class="chart-axis-text" text-anchor="middle">AMER</text>
          <text x="70" y="175" class="chart-axis-text" text-anchor="middle">EMEA</text>
          <text x="115" y="175" class="chart-axis-text" text-anchor="middle">APAC</text>
          <text x="160" y="175" class="chart-axis-text" text-anchor="middle">LATAM</text>
          <text x="205" y="175" class="chart-axis-text" text-anchor="middle">MEA</text>
          <text x="250" y="175" class="chart-axis-text" text-anchor="middle">ANZ</text>
        </svg>
      </div>
    </div>

    <!-- GAUGE + PROGRESS -->
    <div class="panel">
      <div class="panel-inner">
        <div class="panel-header">
          <div class="panel-title">Performance Index</div>
          <div class="panel-badge">COMPOSITE</div>
        </div>
        <div style="display:flex;justify-content:center;margin-bottom:20px;">
          <svg viewBox="0 0 160 100" width="160" height="100">
            <path d="M20,90 A70,70 0 0,1 140,90" fill="none" stroke="rgba(255,255,255,0.05)" stroke-width="14" stroke-linecap="round"/>
            <path d="M20,90 A70,70 0 0,1 140,90" fill="none" stroke="url(#gaugeGrad)" stroke-width="14" stroke-linecap="round"
              stroke-dasharray="0 220"
              style="animation: gaugeAnim 2s cubic-bezier(0.4,0,0.2,1) 0.8s forwards; filter:drop-shadow(0 0 8px rgba(201,168,76,0.6));"/>
            <defs>
              <linearGradient id="gaugeGrad" x1="0" y1="0" x2="1" y2="0">
                <stop offset="0%" stop-color="var(--accent-red)"/>
                <stop offset="50%" stop-color="var(--gold)"/>
                <stop offset="100%" stop-color="var(--accent-green)"/>
              </linearGradient>
            </defs>
            <style>
              @keyframes gaugeAnim { from { stroke-dasharray: 0 220; } to { stroke-dasharray: 170 220; } }
            </style>
            <text x="80" y="85" font-family="Bebas Neue, sans-serif" font-size="28" fill="var(--text-primary)" text-anchor="middle">87.4</text>
            <text x="80" y="98" font-family="JetBrains Mono, monospace" font-size="8" fill="var(--text-muted)" text-anchor="middle" letter-spacing="2">SCORE</text>
          </svg>
        </div>
        <div class="progress-list">
          <div class="progress-item">
            <div class="progress-meta"><span class="progress-name">Product</span><span class="progress-pct">94%</span></div>
            <div class="progress-track"><div class="progress-fill" style="width:94%;background:linear-gradient(90deg,var(--gold-dim),var(--gold-light));box-shadow:0 0 8px rgba(201,168,76,0.4);"></div></div>
          </div>
          <div class="progress-item">
            <div class="progress-meta"><span class="progress-name">Sales</span><span class="progress-pct">82%</span></div>
            <div class="progress-track"><div class="progress-fill" style="width:82%;background:linear-gradient(90deg,#004499,var(--accent-cyan));box-shadow:0 0 8px rgba(0,212,255,0.3);"></div></div>
          </div>
          <div class="progress-item">
            <div class="progress-meta"><span class="progress-name">Marketing</span><span class="progress-pct">76%</span></div>
            <div class="progress-track"><div class="progress-fill" style="width:76%;background:linear-gradient(90deg,#004422,var(--accent-green));box-shadow:0 0 8px rgba(0,255,157,0.3);"></div></div>
          </div>
          <div class="progress-item">
            <div class="progress-meta"><span class="progress-name">Support</span><span class="progress-pct">91%</span></div>
            <div class="progress-track"><div class="progress-fill" style="width:91%;background:linear-gradient(90deg,var(--gold-dim),var(--gold-light));box-shadow:0 0 8px rgba(201,168,76,0.4);"></div></div>
          </div>
        </div>
      </div>
    </div>

    <!-- DATA TABLE -->
    <div class="panel">
      <div class="panel-inner">
        <div class="panel-header">
          <div class="panel-title">Top Accounts</div>
          <div class="panel-badge">BY ARR</div>
        </div>
        <table class="data-table">
          <thead>
            <tr>
              <th>Account</th>
              <th>ARR</th>
              <th>Status</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>Nexus Global</td>
              <td class="td-mono">$4.2M</td>
              <td><span class="status-dot" style="background:var(--accent-green);box-shadow:0 0 6px var(--accent-green);"></span><span style="color:var(--accent-green);font-size:11px;">Healthy</span></td>
            </tr>
            <tr>
              <td>Vertex Systems</td>
              <td class="td-mono">$3.8M</td>
              <td><span class="status-dot" style="background:var(--accent-green);box-shadow:0 0 6px var(--accent-green);"></span><span style="color:var(--accent-green);font-size:11px;">Healthy</span></td>
            </tr>
            <tr>
              <td>Orbit Finance</td>
              <td class="td-mono">$2.9M</td>
              <td><span class="status-dot" style="background:var(--gold);box-shadow:0 0 6px var(--gold);"></span><span style="color:var(--gold);font-size:11px;">At Risk</span></td>
            </tr>
            <tr>
              <td>Quantum Labs</td>
              <td class="td-mono">$2.1M</td>
              <td><span class="status-dot" style="background:var(--accent-green);box-shadow:0 0 6px var(--accent-green);"></span><span style="color:var(--accent-green);font-size:11px;">Healthy</span></td>
            </tr>
            <tr>
              <td>Apex Dynamics</td>
              <td class="td-mono">$1.7M</td>
              <td><span class="status-dot" style="background:var(--accent-red);box-shadow:0 0 6px var(--accent-red);"></span><span style="color:var(--accent-red);font-size:11px;">Churning</span></td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>

  <!-- HEATMAP ROW -->
  <div class="sep" style="margin-top:2px;"></div>
  <div class="panel" style="margin-top:2px;animation: fadeUp 0.9s cubic-bezier(0.16,1,0.3,1) 0.8s both;">
    <div class="panel-inner">
      <div class="panel-header">
        <div class="panel-title">Activity Heatmap — Last 12 Weeks</div>
        <div class="panel-badge">DAILY EVENTS</div>
      </div>
      <div class="heatmap-grid" id="heatmap"></div>
    </div>
  </div>

</div><!-- end shell -->

<script>
  // ─── CURSOR ───────────────────────────────────────────
  const cursor = document.getElementById('cursor');
  const ring = document.getElementById('cursor-ring');
  let mx = 0, my = 0, rx = 0, ry = 0;
  document.addEventListener('mousemove', e => {
    mx = e.clientX; my = e.clientY;
    cursor.style.left = mx + 'px';
    cursor.style.top = my + 'px';
  });
  function animRing() {
    rx += (mx - rx) * 0.12;
    ry += (my - ry) *.12;
    ring.style.left = rx + 'px';
    ring.style.top = ry + 'px';
    requestAnimationFrame(animRing);
  }
  animRing();
  document.querySelectorAll('.kpi-card, .panel, button').forEach(el => {
    el.addEventListener('mouseenter', () => {
      ring.style.width = '60px'; ring.style.height = '60px';
      ring.style.borderColor = 'rgba(201,168,76,0.8)';
    });
    el.addEventListener('mouseleave', () => {
      ring.style.width = '40px'; ring.style.height = '40px';
      ring.style.borderColor = 'rgba(201,168,76,0.5)';
    });
  });

  // ─── CLOCK ────────────────────────────────────────────
  function updateClock() {
    const now = new Date();
    document.getElementById('clock').textContent =
      now.toTimeString().slice(0,8);
    document.querySelector('.hero-meta').textContent =
      `Q4 2024  ·  GLOBAL CONSOLIDATED  ·  UPDATED ${now.toTimeString().slice(0,8)}`;
  }
  setInterval(updateClock, 1000);
  updateClock();

  // ─── COUNTER ANIMATION ───────────────────────────────
  function countTo(el, target, prefix, suffix, duration = 2200, decimals = 0) {
    const start = performance.now();
    function step(ts) {
      const p = Math.min((ts - start) / duration, 1);
      const ease = 1 - Math.pow(1 - p, 4);
      const val = target * ease;
      el.textContent = prefix + (decimals ? val.toFixed(decimals) : Math.round(val).toLocaleString()) + suffix;
      if (p < 1) requestAnimationFrame(step);
    }
    requestAnimationFrame(step);
  }
  setTimeout(() => {
    countTo(document.getElementById('kpi1'), 84.3, '$', 'M', 2200, 1);
    countTo(document.getElementById('kpi2'), 248621, '', '', 2200);
    countTo(document.getElementById('kpi3'), 6.4, '', '%', 2200, 1);
    countTo(document.getElementById('kpi4'), 2.1, '', '%', 2200, 1);
  }, 2700);

  // ─── TICKER ───────────────────────────────────────────
  const tickers = [
    { sym: 'ARR', val: '$84.3M', chg: '+23.4%', up: true },
    { sym: 'NRR', val: '118%', chg: '+4pp', up: true },
    { sym: 'CAC', val: '$1,240', chg: '-8.2%', up: false },
    { sym: 'LTV', val: '$28,400', chg: '+12.1%', up: true },
    { sym: 'GRR', val: '91%', chg: '+2pp', up: true },
    { sym: 'PAYBACK', val: '14mo', chg: '-3mo', up: true },
    { sym: 'BURN', val: '$1.2M', chg: '-15%', up: true },
    { sym: 'RUNWAY', val: '28mo', chg: '+4mo', up: true },
  ];
  const tickerEl = document.getElementById('ticker');
  const doubled = [...tickers, ...tickers];
  tickerEl.innerHTML = doubled.map(t =>
    `<div class="ticker-item"><strong>${t.sym}</strong> ${t.val} <span class="${t.up ? 'up' : 'dn'}">${t.chg}</span></div>`
  ).join('');

  // ─── HEATMAP ──────────────────────────────────────────
  const hm = document.getElementById('heatmap');
  const colors = ['rgba(201,168,76,0.1)','rgba(201,168,76,0.25)','rgba(201,168,76,0.45)','rgba(201,168,76,0.65)','rgba(201,168,76,0.9)'];
  for (let i = 0; i < 84; i++) {
    const cell = document.createElement('div');
    cell.className = 'hm-cell';
    const intensity = Math.random();
    const colorIdx = Math.floor(intensity * colors.length);
    cell.style.background = colors[colorIdx];
    if (intensity > 0.8) cell.style.boxShadow = '0 0 6px rgba(201,168,76,0.4)';
    cell.style.animationDelay = (0.8 + i * 0.01) + 's';
    cell.title = `${Math.round(intensity * 1200)} events`;
    hm.appendChild(cell);
  }

  // ─── PARTICLE FIELD ───────────────────────────────────
  const canvas = document.createElement('canvas');
  canvas.style.cssText = 'position:fixed;inset:0;pointer-events:none;z-index:2;opacity:0.4;';
  document.body.appendChild(canvas);
  const ctx = canvas.getContext('2d');
  let W, H, particles = [];
  function resize() {
    W = canvas.width = window.innerWidth;
    H = canvas.height = window.innerHeight;
  }
  resize();
  window.addEventListener('resize', resize);
  for (let i = 0; i < 60; i++) {
    particles.push({
      x: Math.random() * W, y: Math.random() * H,
      vx: (Math.random() - 0.5) * 0.3, vy: (Math.random() - 0.5) * 0.3,
      r: Math.random() * 1.5 + 0.3,
      alpha: Math.random() * 0.5 + 0.1
    });
  }
  function animParticles() {
    ctx.clearRect(0, 0, W, H);
    particles.forEach((p, i) => {
      p.x += p.vx; p.y += p.vy;
      if (p.x < 0) p.x = W; if (p.x > W) p.x = 0;
      if (p.y < 0) p.y = H; if (p.y > H) p.y = 0;
      ctx.beginPath();
      ctx.arc(p.x, p.y, p.r, 0, Math.PI * 2);
      ctx.fillStyle = `rgba(201,168,76,${p.alpha})`;
      ctx.fill();
      // connect nearby
      particles.slice(i + 1).forEach(q => {
        const dx = p.x - q.x, dy = p.y - q.y;
        const dist = Math.sqrt(dx*dx + dy*dy);
        if (dist < 120) {
          ctx.beginPath();
          ctx.moveTo(p.x, p.y);
          ctx.lineTo(q.x, q.y);
          ctx.strokeStyle = `rgba(201,168,76,${0.08 * (1 - dist/120)})`;
          ctx.lineWidth = 0.5;
          ctx.stroke();
        }
      });
    });
    requestAnimationFrame(animParticles);
  }
  animParticles();

  // ─── LIVE DATA FLUCTUATION ────────────────────────────
  setInterval(() => {
    const kpis = [
      { el: document.getElementById('kpi1'), base: 84.3, prefix: '$', suffix: 'M', dec: 1 },
      { el: document.getElementById('kpi2'), base: 248621, prefix: '', suffix: '', dec: 0 },
    ];
    kpis.forEach(k => {
      const noise = (Math.random() - 0.5) * 0.02 * k.base;
      const val = k.base + noise;
      k.el.textContent = k.prefix + (k.dec ? val.toFixed(k.dec) : Math.round(val).toLocaleString()) + k.suffix;
    });
  }, 3000);
</script>
</body>
</html>
