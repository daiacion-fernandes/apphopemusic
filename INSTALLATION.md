# Guia Completo de Instalação - Hope Music App

## 📋 Pré-requisitos

- OpenCart versão 3.0.x ou 4.0.x
- PHP 7.4 ou superior
- Acesso administrativo ao painel do OpenCart
- 5MB de espaço em disco

## 🔧 Método 1: Instalação via Administrador (Recomendado)

### Passo 1: Download
1. Acesse a página de [Releases](../../releases)
2. Baixe o arquivo `hopemusicapp.ocmod.zip`

### Passo 2: Upload
1. Acesse o painel administrativo: `seu-site.com/admin`
2. Navegue até: **Extensões > Instalador**
3. Clique em **Selecionar arquivo** e escolha o arquivo `.ocmod.zip`
4. Clique em **Continuar**

### Passo 3: Ativação
1. Vá para: **Extensões > Modificações**
2. Localize: "Hope Music App"
3. Clique no ícone verde ✓ para ativar

### Passo 4: Limpar Cache
1. Acesse: **Sistema > Cache**
2. Clique em **Limpar** para atualizar o sistema

## 🔧 Método 2: Instalação Manual (FTP)

### Passo 1: Extrair Arquivos
Extraia o arquivo `.ocmod.zip` em seu computador

### Passo 2: Upload via FTP
1. Conecte-se via FTP ao seu servidor
2. Navegue até a pasta raiz do OpenCart
3. Faça upload de todos os arquivos preservando a estrutura de pastas

### Passo 3: Ativar Extensão
1. Painel Admin > **Extensões > Modificações**
2. Procure por "Hope Music App"
3. Clique no ícone verde para ativar

## ⚙️ Configuração Inicial

### Acessar Configurações
1. Vá para: **Extensões > Hope Music App > Configuração**

### Opções Disponíveis
- **Status**: Ativar/Desativar o aplicativo
- **Posição**: Onde exibir o player musical
- **Tema**: Escolher o estilo do player

## ✅ Verificação de Instalação

Para garantir que tudo está funcionando:

1. **Verificar Ativação**
   - Extensões > Modificações
   - Hope Music App deve estar listado e ativo

2. **Testar Frontend**
   - Visite o site e procure pelo player musical
   - Verifique se está funcionando normalmente

3. **Verificar Logs**
   - Sistema > Logs
   - Não deve haver erros relacionados ao Hope Music App

## 🆘 Solução de Problemas

### Problema: "Arquivo inválido"
**Solução:**
- Certifique-se de que é um arquivo `.ocmod.zip` legítimo
- Verifique a integridade do download
- Tente download novamente

### Problema: "Extension não aparece após instalação"
**Solução:**
1. Limpe o cache: Sistema > Cache > Limpar
2. Atualize a página do navegador (Ctrl+F5)
3. Verifique se as permissões do servidor estão corretas

### Problema: "Erro ao ativar"
**Solução:**
1. Verifique se a versão do OpenCart é compatível
2. Consulte o arquivo de log: `system/logs/`
3. Entre em contato pelo GitHub Issues

## 🗑️ Desinstalação

Para remover o aplicativo:

1. **Via Admin:**
   - Extensões > Modificações
   - Clique no X vermelho para desativar
   - Extensões > Instalador
   - Procure por "Hope Music App" e clique em Desinstalar

2. **Manual:**
   - Remova os arquivos via FTP
   - Limpe o cache do OpenCart

## 📞 Suporte

Precisa de ajuda?
- Abra uma [Issue no GitHub](../../issues)
- Consulte as [Discussões](../../discussions)
- Verifique o [README](README.md)

## 📝 Notas Importantes

- **Backup**: Sempre faça backup antes de instalar
- **Teste**: Instale em ambiente de testes primeiro
- **Compatibilidade**: Verifique a versão do OpenCart antes de instalar
- **Performance**: Teste o site após instalação para garantir performance

---

**Última Atualização:** Junho 2026
