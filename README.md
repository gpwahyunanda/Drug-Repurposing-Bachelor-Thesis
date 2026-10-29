# Drug Repurposing — Ligand-Based Virtual Screening (Bachelor Thesis)

Repositori ini memuat bahan dan hasil skripsi S1 tentang *drug repurposing* terhadap protease utama SARS-CoV-2 (3CLpro/Mpro) memakai **ligand-based virtual screening (LBVS)**.

Diadaptasi dari:
- Tuerkova & Zdrazil (2020), *Drug Repurposing*.
- Sydow et al. (2019), *TeachOpenCADD* (workflow KNIME).

## Isi
| Berkas | Keterangan |
|---|---|
| `3CLpro Active and Inactive Ligands.xlsx` | Ligan aktif dan tidak aktif terhadap 3CLpro |
| `3CLpro All bioactivities from ligand.xlsx` | Seluruh data bioaktivitas ligan |
| `3CLpro Cluster result.xlsx` | Hasil klasterisasi |
| `3CLpro MCS result.xlsx`, `3CLpro MCS Framework result.xlsx`, `3CLpro MCS with Amount of Hits and Its Highest Score.xlsx` | Hasil maximum common substructure (MCS) |
| `3CLpro Prediction score RF.xlsx` | Skor prediksi model Random Forest |
| `LBVS_DrugRepurposing_Workflow_UniProt COVID SMOTE.knwf` | Workflow KNIME (data COVID, SMOTE) |
| `LBVS_DrugRepurposing_Workflow_UniProt Non COVID SMOTE.knwf` | Workflow KNIME (data non-COVID, SMOTE) |

## Cara menjalankan
1. Pasang [KNIME Analytics Platform](https://www.knime.com/).
2. Impor salah satu berkas `.knwf` (`File > Import KNIME Workflow`).
3. Jalankan alur; hasil perantara setara dengan berkas `.xlsx` di atas.

## Catatan
Hasil prediksi bersifat komputasional (hipotesis), bukan bukti klinis, dan memerlukan validasi eksperimen.

## Lisensi
[MIT](LICENSE)
