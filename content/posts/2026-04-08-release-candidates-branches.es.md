---
title: "Release cadidates branches strategy"
date: 2026-04-08T10:00:00+02:00
lastmod: 2026-04-08T10:00:00+02:00
draft: true

# Categorization
tags: ["git", "release candidate", "branch", "strategy"]
categories: ["programming"]

# SEO & social
description: "Advantages and hhow to apply a RC branches strategy."

# Display
author: "Javi"
cover:
  image: "images/cover.jpg"
  alt: "Cover description"
  caption: "Optional caption"

# Optional but useful
toc: true                      # table of contents
weight: 0                      # for ordering within a section
math: false                    # enable KaTeX/MathJax if your theme supports it
---

# Introduction

La estrategia de ramas candidatas a lanzamiento consiste en crear ramas específicas en el repositorio Git que representan versiones consideradas listas para su lanzamiento. Estas ramas se crean a partir de la rama principal de desarrollo en un momento determinado, cuando el conjunto de funcionalidades ha alcanzado la madurez suficiente para preparar una entrega.

En estas ramas, se integran las ramas de características que ya han superado las pruebas iniciales y se someten a un ciclo de validación más exhaustivo: pruebas de integración, pruebas de regresión, controles de calidad y revisiones finales. Si la versión candidata cumple los criterios de calidad, se convierte en la versión oficial que entra en producción. Si se detectan problemas, se corrigen directamente en la rama candidata, evitando que los cambios inestables contaminen el flujo de desarrollo principal.
