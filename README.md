# Dio | Resumos Git e GitHub

Repositorio para armazenar resumos sobre Git e Github do Curso versionamento de codigo com Git E GitHub da [Digital Innovatton One][def]


## 📚 Documentação

- [Documentaçao Git]()
- [Documentaçao GitHub]()

## 💻 Resumos das Aulas

|Aulas | Resumos |
|------|---------|
| Aulas 01| [Resumo]()|
| Aulas 02| [Resumo]()|


## Referencias
- [Digital Innovatton One][def]


## Configurando Chave SSH Ed25519

- Gerar uma nova chave SSH Ed25519  
  `ssh-keygen -t ed25519 -C "seu-email@example.com"`

- Exibir a chave pública para copiar e adicionar ao GitHub  
  `cat ~/.ssh/id_ed25519.pub`

- Iniciar o agente SSH  
  `eval $(ssh-agent -s)`

- Adicionar a chave privada ao agente SSH  
  `ssh-add ~/.ssh/id_ed25519`

[def]: https://www.dio.me/
