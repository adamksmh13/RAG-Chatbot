# ⚙️ Workflow Documentation

## 📥 Workflow 1 --- FAQ Ingestion

### 🎯 Purpose

Mengumpulkan data FAQ dari user dan menyimpannya ke spreadsheet.

### 🔄 Flow

Form Submission → Detect CSV Upload → Extract / Format Data → Save to
Spreadsheet

------------------------------------------------------------------------

## 🤖 Workflow 2 --- AI Chatbot

### 🎯 Purpose

Menjawab pertanyaan client berdasarkan knowledge base FAQ.

### 🔄 Flow

Chat Input → Fetch FAQ Data → AI Processing → Generate Response

------------------------------------------------------------------------

# 📊 Knowledge Base Format

Spreadsheet harus memiliki struktur:

  question   answer
  ---------- --------

------------------------------------------------------------------------

# 📥 CSV Format Example

    question,answer
    Apa itu donasi?,Donasi adalah...
    Bagaimana cara berdonasi?,Caranya adalah...

------------------------------------------------------------------------

# 🛠️ Installation & Setup

## 1️⃣ Import Workflow

1.  Buka dashboard n8n\
2.  Pilih Import Workflow\
3.  Upload file JSON dari folder workflows

------------------------------------------------------------------------

## 2️⃣ Setup Credentials

### Google Sheets

-   Buat OAuth credential
-   Hubungkan spreadsheet knowledge base

### OpenAI

-   Masukkan OpenAI API key
-   Hubungkan ke AI Agent node

------------------------------------------------------------------------

## 3️⃣ Run Workflow

-   Workflow ingestion → menambah FAQ\
-   Workflow chatbot → menjawab pertanyaan

------------------------------------------------------------------------

# 🧪 Testing

## Test FAQ Ingestion

-   Upload CSV\
-   Input FAQ manual\
-   Pastikan data tersimpan di spreadsheet

## Test Chatbot

-   Kirim pertanyaan melalui chat trigger\
-   Pastikan AI menjawab sesuai FAQ

------------------------------------------------------------------------

# 🔐 Security Notes

Repository ini tidak menyimpan: - API Keys\
- OAuth Credentials\
- Environment Variables

Gunakan credential manager di n8n.

------------------------------------------------------------------------

# ⚡ Scalability

Project ini cocok untuk: - FAQ internal perusahaan\
- Customer support automation\
- Knowledge base chatbot

------------------------------------------------------------------------

# 📈 Future Improvements

-   FAQ analytics dashboard\
-   Multi language support\
-   Auto training pipeline\
-   Admin management panel\
-   WhatsApp / Telegram integration

------------------------------------------------------------------------

# 👨‍💻 Contribution

Kontribusi terbuka untuk pengembangan fitur baru, peningkatan workflow,
dan optimasi AI.

------------------------------------------------------------------------

# 📜 License

Project ini dapat digunakan untuk kebutuhan pembelajaran dan
pengembangan automation system.
