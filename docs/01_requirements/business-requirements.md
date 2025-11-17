# Business Requirements Analysis
## Data Mart Portal Satu Data ITERA

---

## 1. Stakeholders

### Primary Stakeholders
- **Tim Pengelola Portal Satu Data**: Maintenance, update dataset, monitoring sistem
- **Management ITERA**: Menggunakan insight untuk decision making strategis
- **Data Stewards**: Unit-unit yang menyediakan dan memvalidasi dataset
- **Pengguna Eksternal**: Peneliti, masyarakat umum yang mengakses open data

### Secondary Stakeholders
- **Mahasiswa**: Mencari dataset untuk tugas, skripsi, penelitian
- **Dosen & Peneliti**: Mengakses data untuk riset dan publikasi
- **Bagian Perencanaan & QA**: Analisis data untuk evaluasi institusi
- **Media & Publik**: Akses informasi publik ITERA untuk transparansi

### Decision Makers
- **Tim Pengelola Portal**: Keputusan terkait dataset prioritas, akses policy
- **Management ITERA**: Keputusan strategis berdasarkan insight data
- **Data Governance Team**: Keputusan terkait data quality, privacy, security

---

## 2. Business Process Analysis

### Proses Pengelolaan Dataset
```
Data Collection → Data Validation → Metadata Creation → Dataset Publication → Update & Maintenance
```

**KPIs**:
- Jumlah dataset baru dipublikasi per bulan
- Waktu rata-rata dari collection hingga publikasi
- Persentase dataset dengan metadata lengkap
- Frekuensi update dataset sesuai schedule

### Proses Akses dan Download Dataset
```
User Registration → Search/Browse → Dataset Preview → Download/API Access → Usage Tracking
```

**KPIs**:
- Jumlah user aktif per bulan (by type: mahasiswa, dosen, publik)
- Total akses dan download dataset
- Conversion rate dari search ke download
- Response time rata-rata untuk akses dataset
- Popular datasets (top 10 most accessed)

### Proses Data Quality Management
```
Quality Assessment → Issue Identification → Data Cleaning → Re-validation → Quality Reporting
```

**KPIs**:
- Data completeness score rata-rata per kategori
- Data accuracy score per dataset
- Persentase dataset dengan quality score > 90%
- Jumlah dataset yang perlu improvement
- Time lag antara data collection dan availability

### Proses Search & Discovery
```
User Query → Search Execution → Results Ranking → Dataset Selection → Feedback Collection
```

**KPIs**:
- Total pencarian per hari/minggu/bulan
- Search success rate (queries with results)
- Popular search keywords
- Average search duration
- Click-through rate untuk hasil pencarian
- Zero-result search rate (queries tanpa hasil)

---

## 3. Analytical Requirements

### Business Questions to Answer

**Dataset Management Analytics**:
1. Berapa jumlah dataset tersedia per kategori?
2. Dataset mana yang paling sering diakses/didownload?
3. Bagaimana kualitas dataset yang tersedia (completeness, freshness)?
4. Kategori dataset apa yang paling banyak dicari?

**User Behavior Analytics**:
5. Siapa pengguna aktif portal (mahasiswa, dosen, publik)?
6. Apa keyword pencarian yang paling populer?
7. Kapan waktu peak usage portal?
8. Dataset apa yang trending dalam periode tertentu?

**Institution Metrics Analytics**:
9. Bagaimana tren jumlah mahasiswa, dosen, program studi?
10. Bagaimana performa institusi dari tahun ke tahun?
11. Apa insight utama yang dapat diberikan kepada management?

**Data Quality Analytics**:
12. Berapa persentase dataset yang up-to-date?
13. Dataset mana yang perlu di-refresh?
14. Bagaimana coverage metadata untuk setiap dataset?

### Report Types
- **Daily**: Monitoring akses dataset, user activity, system performance
- **Weekly**: Laporan dataset baru, trending searches, quality issues
- **Monthly**: Laporan performa portal, user engagement, dataset usage
- **Quarterly**: Laporan quality metrics, data governance compliance
- **Annual**: Laporan tahunan institusi, dataset portfolio review

### Data Granularity
- **Dataset Level**: Per individual dataset (akses, download, quality)
- **User Level**: Per individual user (aktivitas, preferensi)
- **Category Level**: Per kategori dataset (popularitas, kualitas)
- **Organization Level**: Per unit organisasi (kontribusi dataset)
- **Time Level**: Per hari, minggu, bulan, semester, tahun
- **Institution Level**: Agregat institusi (total metrics, KPIs)

---

## 4. Success Metrics

### Portal Performance Metrics
- **Availability**: > 99.5% uptime
- **Response Time**: < 2 seconds untuk search queries
- **Download Speed**: > 5 MB/s untuk dataset downloads
- **API Performance**: < 500ms untuk API calls

### Data Quality Metrics
- **Completeness**: > 95% untuk metadata
- **Accuracy**: > 98% untuk dataset values
- **Timeliness**: < 24 hours untuk dataset updates
- **Consistency**: 100% untuk critical fields

### User Engagement Metrics
- **Active Users**: > 1000 users per month
- **Download Rate**: > 500 downloads per month
- **Search Success Rate**: > 85%
- **User Satisfaction**: > 4.0/5.0

### Dataset Portfolio Metrics
- **Dataset Coverage**: > 80% unit organisasi memiliki dataset
- **Update Frequency**: > 90% dataset di-update sesuai schedule
- **Quality Score**: > 85% dataset dengan quality score > 80%
- **Access Diversity**: > 70% dataset diakses minimal 1x per bulan

---

**Document Information**:
- **Created**: November 2024
- **Version**: 1.0
- **Project**: Data Mart Portal Satu Data ITERA
- **Course**: Pergudangan Data - Institut Teknologi Sumatera
