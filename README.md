# Hello-World
Meus primeiro repositor
Editar, Salvar e Abrir .txt
void Button3Click(object sender, EventArgs e)
		{
			richTextBox1.Clear();
		}
		void Button1Click(object sender, EventArgs e)
		{
			richTextBox1.LoadFile(textBox1.Text, RichTextBoxStreamType.PlainText);
		}
		void Button2Click(object sender, EventArgs e)
		{
			richTextBox1.SaveFile(textBox1.Text, RichTextBoxStreamType.PlainText);
		}
