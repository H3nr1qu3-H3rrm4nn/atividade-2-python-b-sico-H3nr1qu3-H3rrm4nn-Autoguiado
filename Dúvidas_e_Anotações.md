# Lista de dúvidas referentes a essa atividade
(linha 4) def - comando para criar uma função, criamos então uma função de nome 'real_all_databank_core_csv(directory)', a parte "directory" é puramente descritiva para informar qual tipo de informação deve ser colocada entre os parênteses, ou é uma palavra reservada e pré-definida?
(linha 9) dfs={} - o que foi declarado aqui? uma matriz de nome dfs?
(linha 10) files = glob.glob('{}/*.csv'.format(directory)) - criamos uma variável denominada "files" e atribuimos a ela o resultado dos arquivos presentes no diretório especificado após o tratamento feito pelo combando "glob.glob". Imagino que o .csv serve para definir o tipo de arquivo que queremos como saída, mas qual a necessidade da "/" e do *?

