## API dos Professores de Desenvolvimento de Sistemas da Etec Taboão da Serra

Esta API fornece informações sobre os professores e matérias do curso de Desenvolvimento de Sistemas na Etec de Taboão da Serra.

### Endpoints Disponíveis

- `GET /professores`: Retorna uma lista de todos os professores do curso de Desenvolvimento de Sistemas, incluindo seus IDs, nomes e as matérias que ministram.
- `GET /professores/{id}`: Retorna informações detalhadas de um professor específico, incluindo nome, matéria(s) que ministra e ID.
- `GET /materias`: Retorna uma lista de todas as matérias disponíveis no curso, incluindo seus IDs, nomes e URLs relacionadas.
- `GET /materias/{id}`: Retorna informações detalhadas de uma matéria específica, incluindo nome, ID e URL relacionada.
- `GET /escola`: Retorna informações sobre a escola, incluindo seu nome.

### Exemplos de Uso

- **Listar todos os professores**: 
  ```
  GET https://my-json-server.typicode.com/trabalhos-etec/fake-api/professores
  ```

- **Obter informações de um professor específico (ID 2)**: 
  ```
  GET https://my-json-server.typicode.com/trabalhos-etec/fake-api/professores/2
  ```

- **Listar todas as matérias**: 
  ```
  GET https://my-json-server.typicode.com/trabalhos-etec/fake-api/materias
  ```

- **Obter informações de uma matéria específica (ID 1)**: 
  ```
  GET https://my-json-server.typicode.com/trabalhos-etec/fake-api/materias/1
  ```

- **Obter informações sobre a escola**:
  ```
  GET https://my-json-server.typicode.com/trabalhos-etec/fake-api/escola
  ```

### Recursos Externos Relacionados

- [Programação de Aplicativos Mobile](https://www.ibm.com/br-pt/topics/mobile-application-development)
- [Técnicas de Programação e Algoritmos](https://cm-kls-content.s3.amazonaws.com/201802/INTERATIVAS_2_0/ALGORITMOS_E_TECNICAS_DE_PROGRAMACAO/U1/LIVRO_UNICO.pdf)
- [Desenvolvimento de Sistemas](https://www.eniac.com.br/blog/desenvolvimento-de-sistemas-o-que-e-como-funciona-e-mais)
- [Programação Web](https://blog.eseg.edu.br/o-que-e-programacao-web/)
- [Ética e Cidadania Organizacional](https://periodicos.faex.edu.br/index.php/e-Locucao/article/download/278/208/)
- [Banco de Dados](https://www.oracle.com/br/database/what-is-database/)
- [Fundamentos de Informática](https://icdl.org/workforce/fundamentos-informatica/)
- [Design Digital](https://www.cursospm3.com.br/blog/design-digital/)
- [Sistemas Embarcados](http://www.uel.br/pos/ese/?page_id=27)
- [Internet e Protocolos de Sistemas de Informação](https://www.hostmidia.com.br/blog/protocolos-de-internet/)
- [Planejamento e Desenvolvimento do Trabalho de Conclusão de Curso](http://www.etecjosedagnoni.com.br/downloads/Nucleobasico/VOL.3-PLANEJAMENTO_E_DESENVOLVIMENTO_DO_TCC.pdf)
- [Qualidade e Teste de Software](https://www.treinaweb.com.br/blog/importancia-dos-testes-de-software-na-qualidade-do-sistema)

### Observações

- A API é pública e de uso livre.
- Os dados são fornecidos apenas para fins educacionais e informativos.
- Para mais informações sobre a Etec de Taboão da Serra, entre em contato diretamente com a instituição.
