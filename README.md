# Painter

> 2024/12/03

### 存檔

```csharp
private void 儲存檔案ToolStripMenuItem_Click(object sender, EventArgs e)
{
    pictureBox1.Image.Save(@"C:\Users\User\Desktop\1.png", ImageFormat.Png);
}
```


### 紅筆
```csharp=
// 創立 Pen 物件 p
Pen p = new Pen(Color.Black, 3);

private void 紅色ToolStripMenuItem_Click(object sender, EventArgs e)
{
    //修改p為紅色
    p.Color = Color.Red;
}
```
![image](https://github.com/user-attachments/assets/187bef5b-8ca8-416c-a69e-15e3d039b14a)

### 成品
![image](https://github.com/user-attachments/assets/d59859b5-9f9d-4082-9842-d9dbc0bad057)
