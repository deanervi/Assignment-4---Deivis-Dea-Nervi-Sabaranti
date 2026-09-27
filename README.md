CARA RUN LOKAL:
newman run project.json -e env.json

notes: akan terjadi error saat run newman karena email dan password diambil dari Repository secrets dari Github

STRUKTUR FOLDER:
.github/workflows/api-test.yml =  digunakan untuk mengatur CI/CD

project.json = berisi script testing
env.json = berisi env yg disimpan dari hasil script testing
labs-data.csv = berisi test data yang disimpan dari sheets dan digunakan pada skenario data driven testing
