# C-TemelAracKullanimi_Ornek1
Temel araç kullanımı için basit örnek.

namespace Ders_7_ödev
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void label2_Click(object sender, EventArgs e)
        {

        }

        private void label3_Click(object sender, EventArgs e)
        {

        }

        private void button1_Click(object sender, EventArgs e)
        {
            listBox1.Items.Add(textBox1.Text);
            listBox1.Items.Add(textBox2.Text);
            listBox1.Items.Add(maskedTextBox1.Text); 
            listBox1.Items.Add(maskedTextBox2.Text);
            listBox1.Items.Add(comboBox1.Text);
            listBox1.Items.Add(dateTimePicker1.Text);
        }
    }
}
