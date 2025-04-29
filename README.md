# 📝 Resume Matcher CLI (Go)

This is a simple command-line tool written in Go that compares a job description with a resume and outputs a similarity score based on keyword overlap.

## 🚀 How to Use

```bash
go run main.go --job sample_data/job.txt --resume sample_data/resume.txt
```

## 📦 Project Structure

- `main.go` – Core CLI logic
- `sample_data/` – Example job and resume text files
- `assets/demo.png` – (Optional) Screenshot or GIF of the CLI in action

## 🔧 Requirements

- Go 1.17+

## 📸 Demo Output

![CLI Demo](assets/demo.png)

## 📌 Future Enhancements

- Improve tokenizer/normalizer
- Add support for REST API version
- Use TF-IDF or cosine similarity with vector embeddings
"# go_resume_matcher_cli" 
