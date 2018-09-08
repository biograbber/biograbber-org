---
title: Roadmap
weight: 7
pre: ""
chapter: false
---

## Introduction

Biograbber is a free professional video capture software for standards sources of V4L2 (Video for Linux) and UVC (USB Video Class).

There are many free software projects supporting the development of applications capable of capturing video following the standard V4L2. However, the functional development of these projects is very limited and does not meet professional requirements.

Any video device compatible with UVC standard will work with Biograbber, including webcams, but also many other professional capture devices capable of transforming signals HDMI, SDI, VGA, DVI, VHS, S-VHS, etc. to a USB signal compatible with UVC.

## Why

Single source video capture is clearly insufficient in the medical sector. Each time there are more specialties that simultaneously manage several video sources in their daily work. For this reason one of the main functionalities that we wanted to give to our project is to be able to capture an unlimited number of video sources in a synchronized way, so that later they could also be reproduced and treated synchronized.

Our goal is to develop and maintain a solution for video capture using the free standards of v4l2 and focused on the professional field of health sciences and more precisely in the medical field, but probably applicable to many other fields of the capture of video.

## Technology

La aplicación está desarrollada completamente en QT, y no utiliza ningún software propietario o privativo. (Quizás este punto se podría desarrollar algo más por Flavio)

Nuestro desarrollo se basa en un proyecto muy conocido en la comunidad como es guvcview (http://guvcview.sourceforge.net/), haciendo evolucionar el código hacia una aplicación completamente nueva, y con numerosas nuevas funcionalidades.

Para la reproducción del contenido creado, utilizamos el media player MPV (https://mpv.io), que nos ofrece a través de cu C API un integración completa con nuestra aplicación.

Otras tecnologías abiertas utilizadas son: SQLite,....
