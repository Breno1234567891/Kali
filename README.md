# Kali
# Instalação do Kali Linux no VirtualBox

Este repositório documenta a instalação do **Kali Linux** em uma máquina virtual utilizando o **VirtualBox**. Kali é uma distribuição baseada em Debian, voltada para testes de penetração, análise forense e auditoria de segurança.

---

## Requisitos

### Hardware

| Componente | Mínimo | Recomendado |
|------------|--------|-------------|
| CPU        | 1 núcleo | 2+ núcleos |
| RAM        | 2 GB     | 4+ GB       |
| Disco      | 20 GB    | 40+ GB      |

### Software

- [VirtualBox](https://www.virtualbox.org/)
- [ISO oficial do Kali Linux](https://www.kali.org/get-kali/)

---

## 1. Baixar o Kali Linux

Acesse: [https://www.kali.org/get-kali/](https://www.kali.org/get-kali/)

Escolha a imagem ISO "Installer" (64-bit ou 32-bit conforme sua máquina) e faça o download.

---

## 2. Criar a Máquina Virtual

Abra o VirtualBox e siga os passos:

1. **Novo**:
   - Nome: `Kali Linux`
   - Tipo: `Linux`
   - Versão: `Debian (64-bit)`
2. **Memória**: 2 GB (mínimo) ou 4 GB+
3. **Disco rígido**:
   - Criar novo disco virtual agora
   - VDI, dinamicamente alocado
   - Tamanho: 30 GB ou mais

---

## 3. Montar a ISO

Com a VM criada:

1. Vá em **Configurações > Armazenamento**
2. Clique em "Vazio" > ícone do CD > **Escolher imagem de disco**
3. Selecione a ISO do Kali que você baixou

---

## 4. Iniciar a Instalação

Inicie a VM e selecione **Graphical Install** no menu inicial.

### Etapas:

1. **Idioma**: Português (ou outro de sua preferência)
2. **Localização**: Brasil (ou sua região)
3. **Teclado**: Português Brasileiro ABNT2 (ou outro)
4. **Hostname**: `kali`
5. **Domínio**: (pode deixar em branco)
6. **Usuário**:
   - Nome: `usuário` (ou seu nome)
   - Nome de login: `kali` ou outro
7. **Senha**: crie uma senha segura
8. **Particionamento**:
   - Método: "Assistido - usar disco inteiro"
   - Esquema: "Todos os arquivos em uma única partição"
9. **Instalação do sistema**: aguarde a cópia dos arquivos
10. **Gerenciador de pacotes**: aceite as configurações padrão
11. **Instalar o GRUB**: Sim, na partição principal

---

## 5. Primeiro Acesso

Após a instalação e reinicialização:

- Login: usuário configurado
- Senha: definida na instalação

