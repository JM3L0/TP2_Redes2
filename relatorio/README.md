# Relatório Técnico Científico — Artigo Padrão SBC

**Disciplina:** Redes de Computadores II (2026-2)  
**Instituição:** Universidade Federal do Piauí (UFPI) — Campus Senador Helvídio Nunes de Barros (CSHNB)  
**Autor:** João Marcos Sousa Rufino Leal (`jsousarufinoleal@ufpi.edu.br`)  
**Título:** *Estudo Experimental de Desempenho e Sobrecarga de Protocolos Web: Uma Análise Comparativa entre HTTP/1.1, HTTPS/TLS 1.3 e HTTP/3-QUIC sob Degradação Controlada de Canal com Docker e Python*

---

## Estrutura de Arquivos

- `sbc-template.tex`: Código-fonte LaTeX formatado rigorosamente no padrão SBC/SBRC.
- `sbc.sty`: Pacote de estilo oficial da Sociedade Brasileira de Computação (SBC).
- `relatorio.bib`: Base de referências bibliográficas com Tanenbaum (Seção 6.5.11, Seção 6.6.1, Seção 6.6.2) e todas as RFCs do IETF (RFC 793, 7540, 8446, 9000, 9001, 9114).
- `sbc-template.pdf`: Documento final compilado em alta resolução.

---

## Instruções de Compilação

Para compilar o artigo e resolver todas as citações bibliográficas e referências cruzadas:

No terminal (Linux, macOS, WSL ou Windows com MiKTeX/TeX Live):
```bash
cd relatorio
pdflatex -interaction=nonstopmode sbc-template.tex
bibtex sbc-template
pdflatex -interaction=nonstopmode sbc-template.tex
pdflatex -interaction=nonstopmode sbc-template.tex
```

---