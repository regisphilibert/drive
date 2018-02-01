---
title: "Debug Post"
date: 2018-01-17T15:55:37-05:00
layout: debug

resources :
- src : "files/invoice.pdf"
  title : "Instruction Guide"
- src : "**.pdf"
  title : "PDF file #:counter"
  params :
    icon : "pdf"
- src : "documents/*.docx"
  title : "Word file #:counter"
  params :
    icon : "word"
---

What?

{{< test >}}