---
title: The Azure Speech CLI
titleSuffix: Azure Cognitive Services
description: The Speech CLI is a command-line tool for using the Speech service without writing any code. The Speech CLI requires minimal setup, and it's easy to immediately start experimenting with key features of the Speech service to see if your use-cases can be met.
services: cognitive-services
author: nitinme
manager: nitinme
ms.service: cognitive-services
ms.subservice: speech-service
ms.topic: conceptual
ms.date: 01/13/2021
ms.author: nitinme
ms.custom: devx-track-azurecli
---

# What is the Speech CLI?

The Speech CLI is a command-line tool for using the Speech service without writing any code. The Speech CLI requires minimal setup, and it's easy to immediately start experimenting with key features of the Speech service to see if your use-cases can be met. Within minutes, you can run simple test workflows like batch speech-recognition from a directory of files, or text-to-speech on a collection of strings from a file. Beyond simple workflows, the Speech CLI is production-ready and can be scaled up to run larger processes using automated `.bat` or shell scripts.

Most features in the Speech SDK are available in the Speech CLI, and some advanced features and customizations are simplified in the Speech CLI. Consider the following guidance to decide when to use the Speech CLI or the Speech SDK.

Use the Speech CLI when:
* You want to experiment with Speech service features with minimal setup and no code
* You have relatively simple requirements for a production application using the Speech service

Use the Speech SDK when:
* You want to integrate Speech service functionality within a specific language or platform (for example, C#, Python, C++)
* You have complex requirements that may require advanced service requests, or developing custom behavior including response streaming

## Core features

* Speech recognition - Convert speech-to-text either from audio files or directly from a microphone, or transcribe a recorded conversation.

* Speech synthesis - Convert text-to-speech using either input from text files, or input directly from the command line. Customize speech output characteristics using [SSML configurations](speech-synthesis-markup.md), and either [standard or neural voices](speech-synthesis-markup.md#neural-and-custom-voices).

* Speech translation - Translate audio in a source language to text or audio in a target language.

* Run on Azure compute resources - Send Speech CLI commands to run on an Azure remote compute resource using `spx webjob`.

## Get started

To get started with the Speech CLI, see the [quickstart](spx-basics.md). This article shows you how to run some basic commands, and also shows slightly more advanced commands for running batch operations for speech-to-text and text-to-speech. After reading the basics article, you should have enough of an understanding of the syntax to start writing some custom commands, or automating simple Speech service operations.

## Next steps

- Get started with the [Speech CLI quickstart](spx-basics.md)
- [Configure your data store](./spx-data-store-configuration.md)
- Learn how to [run batch operations with the Speech CLI](./spx-batch-operations.md)
