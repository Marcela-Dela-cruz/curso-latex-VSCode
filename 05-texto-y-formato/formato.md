# Texto y formato básico en LaTeX

## Objetivo de la sesión

Que el estudiante aprenda a estructurar el texto dentro de un documento LaTeX utilizando secciones, listas y comandos básicos de formato.

---

## Idea central

En LaTeX **no se da formato con el mouse**, sino con **comandos**. Esto permite documentos consistentes, ordenados y profesionales.

---

## 1. Párrafos y saltos de línea

En LaTeX:

* Un párrafo nuevo se crea dejando **una línea en blanco**
* Un salto de línea manual se logra con `\\`

Ejemplo:

```latex
Este es el primer párrafo.

Este es el segundo párrafo.
```

---

## 2. Secciones del documento

LaTeX organiza el texto jerárquicamente.

Comandos principales:

```latex
\section{Título de sección}
\subsection{Subsección}
\subsubsection{Subsubsección}
```

Ejemplo:

```latex
\section{Introducción}
Este es el texto de la introducción.

\subsection{Antecedentes}
Texto de antecedentes.
```

La numeración se genera automáticamente.

---

## 3. Texto en negritas, cursivas y subrayado

Comandos básicos:

```latex
\textbf{Negritas}
\textit{Cursiva}
\underline{Subrayado}
```

Ejemplo:

```latex
Este texto está en \textbf{negritas} y este en \textit{cursiva}.
```

---

## 4. Listas

### 4.1 Listas sin orden

```latex
\begin{itemize}
  \item Primer elemento
  \item Segundo elemento
\end{itemize}
```

---

### 4.2 Listas numeradas

```latex
\begin{enumerate}
  \item Primer punto
  \item Segundo punto
\end{enumerate}
```

---

## 5. Listas anidadas

```latex
\begin{itemize}
  \item Elemento principal
  \begin{itemize}
    \item Subelemento
  \end{itemize}
\end{itemize}
```

---

## 6. Alineación del texto

```latex
\begin{center}
Texto centrado
\end{center}

\begin{flushleft}
Texto alineado a la izquierda
\end{flushleft}

\begin{flushright}
Texto alineado a la derecha
\end{flushright}
```

---

## Errores comunes

* Usar muchos `\\` en lugar de párrafos
* Escribir comandos mal cerrados
* Intentar dar formato como en Word

---

## Actividad práctica

1. Crear un archivo `texto-formato.tex`
2. Agregar:

   * Una sección
   * Dos subsecciones
   * Una lista numerada
   * Una lista sin orden
   * Texto con negritas y cursiva
3. Compilar el documento

---

## Resultado esperado

El estudiante será capaz de:

* Organizar un documento por secciones
* Usar listas correctamente
* Aplicar formato básico al texto
* Comprender la lógica de escritura en LaTeX
