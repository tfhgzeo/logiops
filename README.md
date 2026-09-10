sudo apt install logiops

systemctl status logid

Ative na inicialização:

sudo systemctl enable logid 



Adicione o alias a baixo no `.zshrc`

alias mouse="sudo logid && sudo systemctl restart logid"

