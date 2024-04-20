Framework

-> instalar Flet (pip install flet)
Django
Flask

1) Titulo Hashzap
2) Botão para iniciar chat
	Popup
		Bem vindo ao Hashazap
		Escrever seu nome
		Entra no chat
3) Chat
	Rebeca entrou no chat
	Mensagens do usuario
4) Campo para enviar mensagem
5) Botao de enviar

Importar bibliotema Flet
 - import flet as ft

Cria uma funçao
 - def main(pagina):
	texto = ft.Text("Hashzap")
	texto_novo = ("Oi testando")
	pagina.add(texto)
	pagina.add(texto_novo)

Usa comando 
- flet.app(main) -> para aplicativo
ft.app(main, viewft.WEB_BROWSER) -> para site
item.oquefazercomele(parametro)

*Por padrao a funçãao que taa no on_click de qualquer botao ela recebe como parametro um evento
