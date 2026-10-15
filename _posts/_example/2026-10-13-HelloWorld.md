---
title: "TryHackMe: NombreSala"
date: 2026-10-15 00:00:00 -0300
categories: [TryHackMe, Writeup]
tags: [tryhackme, web, nmap, sqli]   # técnicas/herramientas usadas, en minúscula
image:
  path: /images/tryhackme_nombresala/room_image.webp
  alt: NombreSala room card
toc: true
comments: false
---

**NombreSala** fue un reto **white-box / black-box** donde empezamos por [primer paso]. Luego, mediante [técnica 1], conseguimos [resultado] y la primera flag. Después descubrimos [vulnerabilidad 2] y la explotamos para la segunda flag. Finalmente, [escalada o RCE] nos dio acceso completo y la flag final.

[![](/images/tryhackme_nombresala/room_card.webp)](https://tryhackme.com/room/nombresala)

## Initial Enumeration

### Nmap

```console
nabil@kali:~$ nmap -sC -sV -p- -oN nmap.txt TARGET_IP
```

[Resumen de puertos y servicios relevantes.]

### Web 80

[Qué se ve al visitar el servicio.]

![](/images/tryhackme_nombresala/web_index.webp)

## First Flag

[Qué se analizó, qué se encontró y cómo se explotó.]

```bash
comando o payload usado
```

[Resultado y flag.]

## Second Flag

[Siguiente vulnerabilidad, evidencia y explotación.]

## Privilege Escalation

[Cómo se escaló privilegios y qué se obtuvo.]

## Final Flag

[Shell, RCE o acceso final.]

## Lessons Learned

- Vulnerabilidad X: por qué ocurre.
- Mitigación: cómo se corrige.
- Herramienta o técnica nueva que aprendí.