#### Spring Initialzr 

[Spring Initialzr] é utilizado para criar projetos com Sprint Boot


#### Spring Anotations

| Anotação | Objetivo |
| ----- | ----- |
| @Component | Qualquer tipo de bean gerenciado pelo Spring| 
| @Service | Classes com regras de negócio | 
| @Repository | Classes de acesso a banco de dados | 
| @Autowired | Injeção de variável anotada | 


| Anotação MVC (request) | Objetivo |
| ----- | ----- |
| @Controller | Classes de recursos que fornecem endpoints| 
| @RequestMapping | Mapear URLs de acesso ao controller e aos métodos| 
| @PathVariable | Extrair da URL um parâmetro incluído como path da URL | 
| @RequestParam | Capturar um parâmetro de consulta (query param) GET | 
| @ModelAttribute | Usado como variável de retorno de métodos | 
| @Valid | Validação de dados de objetos em parâmetros | 

#### MVC (response)

- ModelMap: Enviar dados a página como resposta de uma solicitação
  - String method(ModelMap model)
  - model.attribute("variavel", objeto)

- ModelAndView: Enviar dados a página como resposta de uma solicitação
  - ModelAndView method()
  - ModelAndView model = new ModelAndView("view")
  - model.addObject("variavel", objeto)


[Spring Initialzr]: <https://start.spring.io/>


