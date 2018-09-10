---
title: Overview
weight: 1
pre: ""
chapter: false
---

<table>
<tr>
<td> <img src="/images/capture1.jpg" alt="Drawing" /> </td>
<td> <img src="/images/capture2.jpg" alt="Drawing" /> </td>
</tr>
<tr>
<td> <img src="/images/capture3.jpg" alt="Drawing" /> </td>
<td> <img src="/images/capture4.jpg" alt="Drawing" /> </td>
</tr>
</table>

## Introduction

Free open source professional video capture software for standards sources of V4L2 (Video for Linux) and UVC (USB Video Class).

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

## Features

Biograbber is full of features that facilitate the capture and processing of the obtained video.

Its main features are:

### Multiple sources

Biograbber allows the configuration of an unlimited number of V4L2 sources, for its capture simultaneously. Although our graphic interface is adapted, in order to have an application as practical as possible we have decided to limit the total number of sources captured to 16.

### Content synchronization

The recordings obtained for each source simultaneously can then be viewed, scanned and saved in a synchronized manner. This allows us, for example, to obtain keyframes of each of the sources in a synchronized way.

### Multi-instance

Multiple instances of our application can be opened simultaneously, using different configurations. For example, if we have 8 video sources, but we want to deal with them in groups of 4, we can have 2 separate instances of Biograbber, with their different configurations applied and execute them from the command line independently.

### Detailed customization of each source

For each source you can configure a whole set of parameters that source offers and always following the V4L2 standard. As an example:

#### Device Input

Most of the devices V4L2 have a single device input, but some offer 2 signals, being able to select which of the 2 we want to use. This usually occurs in devices that capture various types of sources, and Biograbber will automatically show you this settings in devices with these features.

#### Camera output

#### Capture resolution

#### Sampling frequency (FPS)

#### Compression codec

#### Applicable filters

#### Audio source (Standard Portaudio)

#### Audio Rate, Channels, Latency

#### Audio Codec

#### Destination Folder

Nombre genérico autoincrementable para las grabaciones de video y nombre generico autoincrementable para las capturas de imagen estáticas, asi como diferentes tipos de formato de archivo obtenibles.

#### Maximum duration of the recording

#### Streaming as video source

### Keyframes

You can obtain frames from each of video sources, in the most standard formats of the market. You can also get frames from all sources at the same time, which are synchronized. We can obtain frames, from the source itself, from the reproductions of the obtained files, even from the playback of streaming content.

Obtaining these frames from the playback of a video file will automatically create a collection of keyframes, which can then be used to explore the video file more efficiently.

### Integrated video playback

No need of external applications to be able to play our recordings. We have integrated the media player MPV API into Biograbber. The reproduction of the recordings obtained in a synchronized way will also be done in the same way. We can also configure each player of each source to show the content with the filters and settings that we want.

### Recording Archive

We can track recordings obtained, and all the recordings synchronized with them, giving them also a name, a description and some labels, for their later filing and location.

### Touch Responsive

In order to facilitate the use of touch screens our system in touch responsive and responds to the most generic gestures of use of touch systems.