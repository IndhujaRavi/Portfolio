---
date: '3'
title: 'Speech Transcription and Text Summarization using AWS'
cover: './architecture.png'
github: ''
external: ''
tech:
  - Python
  - Boto3
  - Amazon EC2
  - AWS lambda
  - Amazon S3
  - Amazon Redshift
  - Amazon SES
  - Amazon Elastic Blockstore
  - Amazon Transcribe
  - Summarizer API
showInProjects: true
---

This application takes as input audio files (or live records audio) and provides two outputs. One is the transcription of the audo file and the other is a short summary of the key points in the audio. These three files involved(audio, transcription and summary) are available for each user on their dashboard who has permissions to manage their files. This application was targeted mainly for students so they can put their pens down and pay complete attention to their lectures. By simply using the record feature, they will have their transcription and summaries which they can refer to at any time. They also automatically receive these files via email as soon as they upload their audio or stop live recording.