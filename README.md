<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <title> Contato - Barbearia Alura</title>

        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
    </head>

    <body>
        <header>
            <div class="caixa">
                <h1> <img src="logo.png" alt="logo da Barbearia Alura"> </h1>

                <nav>
                    <ul>
                        <li><a href="Index.html">Home</a></li>
                        <li><a href="produtos.html">Produtos </a></li>
                        <li><a href="contato.html">Contato</a></li>
                    </ul>
                </nav>
            </div>
        </header>

        <main>
            <form>
                <label for="Nome e sobrenome">Nome e sobrenome</label>
                <input type="text" id="Nome e sobrenome" class="input-padrao" required>

                <label for="Email">Email</label>
                <input type="email" id="Email"class="input-padrao" required placeholder="seuemail@dominio.com">

                <label for="Telefone">Telefone</label>
                <input type="tel" id="Telefone"class="input-padrao" required placeholder="(XX) XXXXX-XXXX">

                <label for="Mensagem">Mensagem</label>
                <textarea cols="70" rows="10" id="Mensagem"class="input-padrao" required> </textarea>

                <fieldset>
                    <legend>Como prefere o nosso contato?</legend>
                    <label for="radio-email"><input type="radio" name="contato" value="email" id="radio-email">Email</label>

                    <label for="radio-telefone"><input type="radio" name="contato" value="telefone" id="radio-telefone">Telefone</label>

                    <label for="radio-whatsapp"><input type="radio" name="contato" value="whatsapp" id="radio-whatsapp" checked>WhatsApp</label>

                </fieldset>

                <fieldset>
                    <legend>Qual horário prefere ser atendido?</legend>
                    <select>
                        <option>Manhã</option>
                        <option>Tarde</option>
                        <option>Noite</option>
                    </select>
                </fieldset>

                <label class="checkbox"><input type="checkbox"checked>Gostaria de receber nossas novidades por email?</label>

                <input type="submit" value="Enviar formulário" class="enviar">

            </form>

            <table>
                <thead>
                    <tr>
                        <th>Dia</th>
                        <th>Horário</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Segunda</td>
                        <td>8h ~ 20h</td>
                    </tr>
                    <tr>
                        <td>Quarta</td>
                        <td>8h ~ 20h</td>
                    </tr>
                    <tr>
                        <td>Sexta</td>
                        <td>8h ~ 20h</td>
                    </tr>
                </tbody>
            </table>

        </main>

                <footer>
            <img src="logo-branco.png" alt="logo da Barbearia Alura">
            <p class="copyright">&copy; Copyright Barbearia Alura - 2019</p>
        </footer>
    </body>
</html>
    <link rel="stylesheet" href="reset.css">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="caixa">
            <h1><img src="logo.png"></h1>

            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="produtos.html">Produtos</a></li>
                    <li><a href="contato.html">Contato</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <ul class="produtos">
            <li>
                <h2>Cabelo</h2>
                <img src="cabelo.jpg">
                <p class="produto-descricao">Na tesoura ou máquina, como o cliente preferir</p>
                <p class="produto-preco">R$ 25,00</p>
            </li>
            <li>
                <h2>Barba</h2>
                <img src="barba.jpg">
                <p class="produto-descricao">Corte e desenho profissional de barba</p>
                <p class="produto-preco">R$ 18,00</p>
            </li>
            <li>
                <h2>Cabelo + Barba</h2>
                <img src="cabelo+barba.jpg">
                <p class="produto-descricao">Pacote completo de cabelo e barba</p>
                <p class="produto-preco">R$ 35,00</p>
            </li>
        </ul>
    </main>

    <footer>
        <img src="logo-branco.png">
        <p class="copyright">&copy; Copyright Barbearia Alura - 2019</p>
    </footer>
</body>
    <link rel="stylesheet" href="reset.css">
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <header>
        <div class="caixa">
            <h1> <img src="logo.png" alt="logo da Barbearia Alura"> </h1>

            <nav>
                <ul>
                    <li><a href="Index.html">Home</a></li>
                    <li><a href="produtos.html">Produtos </a></li>
                    <li><a href="contato.html">Contato</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <form>
            <label for="Nome e sobrenome">Nome e sobrenome</label>
            <input type="text" id="Nome e sobrenome" class="input-padrao" required>

            <label for="Email">Email</label>
            <input type="email" id="Email"class="input-padrao" required placeholder="seuemail@dominio.com">

            <label for="Telefone">Telefone</label>
            <input type="tel" id="Telefone"class="input-padrao" required placeholder="(XX) XXXXX-XXXX">

            <label for="Mensagem">Mensagem</label>
            <textarea cols="70" rows="10" id="Mensagem"class="input-padrao" required> </textarea>

            <fieldset>
                <legend>Como prefere o nosso contato?</legend>
                <label for="radio-email"><input type="radio" name="contato" value="email" id="radio-email">Email</label>

                <label for="radio-telefone"><input type="radio" name="contato" value="telefone" id="radio-telefone">Telefone</label>

                <label for="radio-whatsapp"><input type="radio" name="contato" value="whatsapp" id="radio-whatsapp" checked>WhatsApp</label>

            </fieldset>

            <fieldset>
                <legend>Qual horário prefere ser atendido?</legend>
                <select>
                    <option>Manhã</option>
                    <option>Tarde</option>
                    <option>Noite</option>
                </select>
            </fieldset>

            <label class="checkbox"><input type="checkbox"checked>Gostaria de receber nossas novidades por email?</label>

            <input type="submit" value="Enviar formulário" class="enviar">

        </form>

        <table>
            <thead>
                <tr>
                    <th>Dia</th>
                    <th>Horário</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Segunda</td>
                    <td>8h ~ 20h</td>    <link rel="stylesheet" href="reset.css">
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <header>
        <div class="caixa">
            <h1> <img src="logo.png" alt="logo da Barbearia Alura"> </h1>

            <nav>
                <ul>
                    <li><a href="Index.html">Home</a></li>
                    <li><a href="produtos.html">Produtos </a></li>
                    <li><a href="contato.html">Contato</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <form>
            <label for="Nome e sobrenome">Nome e sobrenome</label>
            <input type="text" id="Nome e sobrenome" class="input-padrao" required>

            <label for="Email">Email</label>
            <input type="email" id="Email"class="input-padrao" required placeholder="seuemail@dominio.com">

            <label for="Telefone">Telefone</label>
            <input type="tel" id="Telefone"class="input-padrao" required placeholder="(XX) XXXXX-XXXX">

            <label for="Mensagem">Mensagem</label>
            <textarea cols="70" rows="10" id="Mensagem"class="input-padrao" required> </textarea>

            <fieldset>
                <legend>Como prefere o nosso contato?</legend>
                <label for="radio-email"><input type="radio" name="contato" value="email" id="radio-email">Email</label>

                <label for="radio-telefone"><input type="radio" name="contato" value="telefone" id="radio-telefone">Telefone</label>

                <label for="radio-whatsapp"><input type="radio" name="contato" value="whatsapp" id="radio-whatsapp" checked>WhatsApp</label>

            </fieldset>

            <fieldset>
                <legend>Qual horário prefere ser atendido?</legend>
                <select>
                    <option>Manhã</option>
                    <option>Tarde</option>
                    <option>Noite</option>
                </select>
            </fieldset>

            <label class="checkbox"><input type="checkbox"checked>Gostaria de receber nossas novidades por email?</label>

            <input type="submit" value="Enviar formulário" class="enviar">

        </form>

        <table>
            <thead>
                <tr>
                    <th>Dia</th>
                    <th>Horário</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Segunda</td>
                    <td>8h ~ 20h</td>
                </tr>
                <tr>
                    <td>Quarta</td>
                    <td>8h ~ 20h</td>
                </tr>
                <tr>
                    <td>Sexta</td>
                    <td>8h ~ 20h</td>
                </tr>
            </tbody>
        </table>

    </main>

            <footer>
        <img src="logo-branco.png" alt="logo da Barbearia Alura">
        <p class="copyright">&copy; Copyright Barbearia Alura - 2019</p>
    </footer>
</body>    <link rel="stylesheet" href="reset.css">
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <header>
        <div class="caixa">
            <h1> <img src="logo.png" alt="logo da Barbearia Alura"> </h1>

            <nav>
                <ul>
                    <li><a href="Index.html">Home</a></li>
                    <li><a href="produtos.html">Produtos </a></li>
                    <li><a href="contato.html">Contato</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <form>
            <label for="Nome e sobrenome">Nome e sobrenome</label>
            <input type="text" id="Nome e sobrenome" class="input-padrao" required>

            <label for="Email">Email</label>
            <input type="email" id="Email"class="input-padrao" required placeholder="seuemail@dominio.com">

            <label for="Telefone">Telefone</label>
            <input type="tel" id="Telefone"class="input-padrao" required placeholder="(XX) XXXXX-XXXX">

            <label for="Mensagem">Mensagem</label>
            <textarea cols="70" rows="10" id="Mensagem"class="input-padrao" required> </textarea>

            <fieldset>
                <legend>Como prefere o nosso contato?</legend>
                <label for="radio-email"><input type="radio" name="contato" value="email" id="radio-email">Email</label>

                <label for="radio-telefone"><input type="radio" name="contato" value="telefone" id="radio-telefone">Telefone</label>

                <label for="radio-whatsapp"><input type="radio" name="contato" value="whatsapp" id="radio-whatsapp" checked>WhatsApp</label>

            </fieldset>

            <fieldset>
                <legend>Qual horário prefere ser atendido?</legend>
                <select>
                    <option>Manhã</option>
                    <option>Tarde</option>
                    <option>Noite</option>
                </select>
            </fieldset>

            <label class="checkbox"><input type="checkbox"checked>Gostaria de receber nossas novidades por email?</label>

            <input type="submit" value="Enviar formulário" class="enviar">

        </form>

        <table>
            <thead>
                <tr>
                    <th>Dia</th>
                    <th>Horário</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Segunda</td>
                    <td>8h ~ 20h</td>
                </tr>
                <tr>
                    <td>Quarta</td>
                    <td>8h ~ 20h</td>
                </tr>
                <tr>
                    <td>Sexta</td>
                    <td>8h ~ 20h</td>
                </tr>
            </tbody>
        </table>

    </main>

            <footer>
        <img src="logo-branco.png" alt="logo da Barbearia Alura">
        <p class="copyright">&copy; Copyright Barbearia Alura - 2019</p>
    </footer>
</body>
                </tr>
                <tr>
                    <td>Quarta</td>
                    <td>8h ~ 20h</td>
                </tr>
                <tr>
                    <td>Sexta</td>
                    <td>8h ~ 20h</td>
                </tr>
            </tbody>
        </table>

    </main>

            <footer>
        <img src="logo-branco.png" alt="logo da Barbearia Alura">
        <p class="copyright">&copy; Copyright Barbearia Alura - 2019</p>
    </footer>
</body>
