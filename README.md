##                                                                                             C# Completo e Profissional-Aplicativos

​											                <img src="https://www.stickersdevs.com.br/wp-content/uploads/2022/01/c-sharp-adesivo-sticker.png" alt="C# adesivo sticker – Stickers Devs" style="zoom:33%;" />

> Índice 
>
> 1. Conhecendo e preparando o ambiente de desenvolvimento
>
>    1.1  Conhecendo a Estrutura do Um Projeto C#
>
> 2. Compilação e Execução de Codigo

## Aulas < 2. Conhecendo e preparando o ambiente de desenvolvimento - 5 >

 

#### **1- Conhecendo a Estrutura do Um Projeto C#**

> Estrutura criada automaticamente na criação de um projeto Windows Form 
>
> ```c#
> using System;
> using System.Collections.Generic;
> using System.ComponentModel;
> using System.Data;
> using System.Drawing;
> using System.Linq;
> using System.Text;
> using System.Threading.Tasks;
> using System.Windows.Forms;
> 
> namespace primeiroProjeto
> {
>     public partial class Form1 : Form
>     {
>         public Form1()
>         {
>             InitializeComponent();
>         }
>     private void Form1_Load(object sender, EventArgs e)
>     {
> 
>     }
>    }
>  }
> ```

#### **2- Compilação e Execução de Codigo**

> Ato de transformar linguagem em código de maquina para serem visualizados. Nesse exemplo esta sendo utilizado Visual Studio 2022 < F5 ou Ctl + F5 >