class Pedido:
  def __init__(self, nome_cliente, telefone_cliente, endereco_cliente, sabor_pizza, tamanho_pizza):
      self.nome_cliente = nome_cliente
      self.telefone = telefone_cliente
      self.endereco = endereco_cliente
      self.sabor = sabor_pizza
      self.tamanho = tamanho_pizza

class Pizzaria:
  def __init__(self):
      self.lista_pedidos = []
      self.lista_sabores = ["Calabresa", "Portuguesa", "Frango com Catupiry", "Marguerita", "Quatro Queijos", "Peperoni"]

  def cadastrar_pedido(self):
      nome_cliente = input("Nome do cliente: ")
      telefone_cliente = input("Número para contato: ")
      endereco_cliente = input("Endereço de entrega: ")
      print("Escolha o sabor da pizza: ")
      for i, sabor in enumerate(self.lista_sabores, 1):
          print(f"{i}. {sabor}")
      opcao = int(input("Digite o número correspondente ao sabor da pizza: "))
      sabor_pizza = self.lista_sabores[opcao - 1]
      tamanho_pizza = input("Escolha o tamanho da pizza: ")
      pedido = Pedido(nome_cliente, telefone_cliente, endereco_cliente, sabor_pizza, tamanho_pizza)
      self.lista_pedidos.append(pedido)
      print("Pedido cadastrado com sucesso!")

  def exibir_pedidos(self):
      print ("Lista de pedidos: ")
      for i, pedido in enumerate(self.lista_pedidos, 1):
          print(f"{i}. Cliente: {pedido.nome_cliente}, Sabor: {pedido.sabor}, Tamanho: {pedido.tamanho}")

  def executar_programa(self):
      print("Bem-vindo à Pizzaria Macciato!")
      while True:
          print("\nOpções: ")
          print("1. Cadastrar Pedido")
          print("2. Exibir Lista de Pedidos")
          print("3. Sair")
          opcao = input("Escolha uma opção: ")

          if opcao == "1":
              self.cadastrar_pedido()

          elif opcao == "2":
              self.exibir_pedidos()

          elif opcao == "3":
              print("Obrigado por utilizar o sistema da Pizzaria Macciato! Até logo!")
              break

          else:
              print("Opção inválida. Por favor, escolha uma opção válida.")

def main():
  pizzaria = Pizzaria()
  pizzaria.executar_programa()

if __name__ == "__main__":
  main()
