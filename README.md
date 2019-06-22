# rsfs
Simples gerenciador de arquivos, feito na disciplina de Laboratorio de Sistemas Operacionais, UFSCar Sorocaba

Modo de uso:

Compilar: gcc shell.c fs.c disk.c -o rsfs

Executar: ./rsfs <imagem> <tamanho> 
  Imagem: é o arquivo contendo a imagem do disco.
  Tamanho: (opcional) é o tamanho da imagem em MB.
  
  Opções do shell:
    format: Formata o sistema de arquivos.
    list: Lista o conteúdo do sistema de arquivos.
    create FILE: Cria o arquivo FILE com tamanho 0.
    remove FILE: Remove o arquivo FILE.
    
    ~ à fazer ~
    copy FILE1 FILE2: Copia o arquivo FILE1 para o arquivo FILE2.
    copyf REAL_FILE FILE: Copia um arquivo “real” chamado REAL_FILE para dentro do ambiente simulado com nome FILE.
    copyt FILE REAL_FILE: Copia um arquivo FILE no ambiente simulado para o um arquivo “real” com nome REAL_FILE.
    exit: Sai do shell.
