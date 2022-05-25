# Arch verde GRUB tema 🎨
 Extraia os arquivos para Área de Trabalho,depois abra o terminal digite o 
 comando para abrir o genciador de arquivos do seu sistema,vá até a pasta /boot/grub/themes 
 e cole o tema Arch,atualize o grub com os comandos:
 
sudo grub-mkconfig -o /boot/grub/grub.cfg

update-grub



#############################################

se não funcionar,instale o grub-customizer :

sudo pacman -S grub-customizer

despois verifique se há algo de errado em configurações avançadas.

#############################################


"Erros comuns"
não localiza o arquivo theme.txt
papel de parede errado,

Edite e salve tudo certinho,Por fim reinicie.

Para baixar pelo terminal :

git clone https://github.com/LuanSouza28/Arch.git
