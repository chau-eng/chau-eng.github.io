---
layout: default
title: Trang chủ
permalink: /
---

<style>
  .hero-section {
    text-align: center;
    padding: 50px 20px;
    background: #f8fafc;
    border-radius: 8px;
    margin-bottom: 30px;
    border: 1px solid #e2e8f0;
  }
  .hero-title {
    font-size: 2rem;
    font-weight: 800;
    margin-bottom: 10px;
    color: #0f172a;
  }
  .hero-subtitle {
    font-size: 1.1rem;
    color: #475569;
    margin-bottom: 20px;
  }
  .btn-group {
    display: flex;
    justify-content: center;
    gap: 12px;
  }
  .btn-main {
    padding: 9px 20px;
    border-radius: 6px;
    text-decoration: none;
    font-weight: 600;
    font-size: 0.95rem;
  }
  .btn-primary { background: #2563eb; color: #fff !important; }
  .btn-secondary { background: #fff; color: #2563eb !important; border: 1px solid #2563eb; }
  
  .section-block { margin-bottom: 40px; }
  .section-heading {
    text-align: center;
    text-transform: uppercase;
    font-weight: 700;
    margin-bottom: 20px;
    border-bottom: 2px solid #e2e8f0;
    padding-bottom: 8px;
  }
  .grid-3 {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 16px;
  }
  .card-box {
    border: 1px solid #e2e8f0;
    border-radius: 6px;
    padding: 20px 15px;
    text-align: center;
    background: #fff;
  }
  .card-box h3 { margin-top: 0; font-size: 1.15rem; color: #1e293b; }
  .tag-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 10px;
  }
  .tech-tag {
    padding: 6px 14px;
    background: #f1f5f9;
    border: 1px solid #cbd5e1;
    border-radius: 16px;
    font-size: 0.9rem;
    text-decoration: none;
    color: #334155;
  }
</style>

<div class="hero-section">
  <div class="hero-title">CBS — STRUCTURAL ENGINEERING</div>
  <div class="hero-subtitle">Công cụ & kiến thức cho kỹ sư kết cấu</div>
  <div class="btn-group">
    <a href="/cbs-tool" class="btn-main btn-primary">CBS Tool</a>
    <a href="/portfolio" class="btn-main btn-secondary">Xem Portfolio</a>
  </div>
</div>

<div class="section-block">
  <h2 class="section-heading">CBS TOOL</h2>
  <div class="grid-3">
    <div class="card-box">
      <h3>BEAM</h3>
      <p>Tự động hóa tính toán & kiểm tra dầm BTCT / thép.</p>
    </div>
    <div class="card-box">
      <h3>COLUMN</h3>
      <p>Phân tích biểu đồ tương tác, tính toán cốt thép cột.</p>
    </div>
    <div class="card-box">
      <h3>DRAW</h3>
      <p>Xuất bản vẽ chi tiết & bảng thống kê tự động.</p>
    </div>
  </div>
</div>

<div class="section-block">
  <h2 class="section-heading">PORTFOLIO</h2>
  <p style="text-align: center; color: #64748b;">Tổng hợp các công trình, giải pháp tự động hóa thiết kế và nghiên cứu ứng dụng.</p>
  <div style="text-align: center; margin-top: 10px;">
    <a href="/portfolio" style="font-weight: 600;">Xem chi tiết tất cả dự án &rarr;</a>
  </div>
</div>

<div class="section-block">
  <h2 class="section-heading">HƯỚNG DẪN</h2>
  <div class="tag-container">
    <a href="/huong-dan" class="tech-tag">AutoCAD</a>
    <a href="/huong-dan" class="tech-tag">Excel</a>
    <a href="/huong-dan" class="tech-tag">Revit</a>
    <a href="/huong-dan" class="tech-tag">SAP2000</a>
    <a href="/huong-dan" class="tech-tag">Python</a>
    <a href="/huong-dan" class="tech-tag">CBS Tool</a>
  </div>
</div>

<div class="section-block">
  <h2 class="section-heading">KẾT CẤU</h2>
  <p style="text-align: center; color: #64748b;">Bài viết về kết cấu thép, bê tông, tiêu chuẩn thiết kế và tính toán.</p>
  <div style="text-align: center; margin-top: 10px;">
    <a href="/ket-cau" style="font-weight: 600;">Xem danh mục bài viết &rarr;</a>
  </div>
</div>
