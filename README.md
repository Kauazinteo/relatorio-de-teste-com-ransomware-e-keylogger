Para começar, criei alguns arquivos de teste em um diretório isolado. Depois, escrevi um script em Python que usou a biblioteca cryptography para criptografar esses arquivos, tornando-os ilegíveis. Foi bem interessante ver como isso funcionava na prática! No final, o script gerou uma mensagem de "resgate" (chamada de LEIA-ME-CRIPTOGRAFADO.txt) para simular a exigência de um pagamento. Também implementei uma função de descriptografia, usando uma chave mestra que eu conhecia, o que mostrou que o verdadeiro problema com esse tipo de ataque é como gerenciar essa chave de forma segura.

Simulação do Keylogger
Depois, passei para a parte do Keylogger, que é basicamente um programa que captura tudo que você digita. Usei a biblioteca pynput para registrar as teclas digitadas em um arquivo de log oculto (sistema_log.txt). O mais legal foi que configurei o script para enviar periodicamente esse log para um e-mail de teste, simulando como um hacker receberia as informações. Isso me fez perceber como a vulnerabilidade humana ou falhas na segurança podem permitir que dados importantes "escapem".

Reflexões sobre Defesa e Prevenção
Depois de fazer essas simulações, ficou muito mais claro como podemos nos defender. Aprendi que a segurança contra ameaças como essas precisa ser em camadas. A primeira linha de defesa é a conscientização do usuário — evitar clicar em links suspeitos é fundamental para impedir que o código malicioso seja executado. Também é super importante usar soluções de segurança em endpoints que analisam o comportamento, não só as assinaturas, para detectar coisas como a criptografia em massa do Ransomware ou conexões SMTP não autorizadas do Keylogger.

E claro, fazer backups regulares e mantê-los offline é a única maneira de garantir que um ataque de Ransomware não cause perda de dados. Assim, podemos restaurar tudo sem precisar pagar o resgate. Monitorar o tráfego de rede com um firewall também é crucial para barrar a exfiltração de dados.

Conclusão
Em resumo, esse desafio do curso Santander me fez entender melhor como o código malicioso funciona na prática. O que eu realmente aprendi é que a combinação de boas ferramentas de segurança e usuários bem informados é o que nos protege no dia a dia. Estou animado para continuar aprendendo mais sobre segurança cibernética!
