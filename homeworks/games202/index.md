<table>
    <tr>
        <td align='center'><img src='./images/games202.jpg'/></td>
    </tr>

</table>

# GAMES202 Lab0

<table>
    <tr>
        <td align='center'><img src='./images/00_01.jpg'/></td>
    </tr>
    <tr>
        <td align='center'><img src='./images/00_02.jpg'/></td>
    </tr>
</table>

# GAMES202 Lab1

<table border="0">
    <tr>
        <td align='center'>SM</td>
        <td align='center'>MutilSM</td>
    </tr>
    <tr>
        <td align='center'><img src='./images/01_SM_renzhixiong.jpg'/></td>
        <td align='center'><img src='./images/01_MutilSM_renzhixiong.jpg'/></td>
    </tr>
    <tr>
        <td align='center'>PCF</td>
        <td align='center'>PCSS</td>
    </tr>
    <tr>
        <td align='center'><img src='./images/01_PCF_renzhixiong.jpg'/></td>
        <td align='center'><img src='./images/01_PCSS_renzhixiong.jpg'/></td>
    </tr>
    <tr>
        <td align='center' colspan=2><b>RotSM</b></td>
    </tr>
    <tr>
        <td align='center' colspan=2><img src='./images/01_RotSM_renzhixiong.gif'/></td>
    </tr>
</table>

# GAMES202 Lab2

## 完成内容

1. 预计算环境光照
2. 预计算 Diffuse Unshadowed LT
3. Diffuse Shadowed LT
4. 预计算数据使用
5. Bonus 1
6. Bonus 2

## 环境光

<table border="0">
    <tr>
        <td align='center'><img src='./images/02_PRT_Shadowed_sample01.jpg'/></td>
        <td align='center'><img src='./images/02_PRT_Shadowed_sample02.jpg'/></td>
        <td align='center'><img src='./images/02_PRT_Shadowed_sample03.jpg'/></td>
    </tr>
</table>

### PRT

<table border="0">
    <tr>
        <td align='center' colspan=2><b>GraceCathedral</b></td>
    </tr>
    <tr>
        <td align='center'>unshadowed</td>
        <td align='center'>shadowed</td>
    </tr>
    <tr>
        <td align='center'><img src='./images/02_PRT_Unshadowed_gracecathedral.jpg'/></td>
        <td align='center'><img src='./images/02_PRT_Shadowed_gracecathedral.jpg'/></td>
    </tr>
    <tr>
        <td align='center'>interreflection</td>
        <td align='center'>scene</td>
    </tr>
    <tr>
        <td align='center'><img src='./images/02_PRT_InterRef_gracecathedral.jpg'/></td>
        <td align='center'><img src='./images/02_PRT_InterRef_gracecathedral_scene.jpg'/></td>
    </tr>
</table>

<table border="0">
    <tr>
        <td align='center' colspan=2><b>Indoor</b></td>
    </tr>
    <tr>
        <td align='center'>unshadowed</td>
        <td align='center'>shadowed</td>
    </tr>
    <tr>
        <td align='center'><img src='./images/02_PRT_Unshadowed_indoor.jpg'/></td>
        <td align='center'><img src='./images/02_PRT_Shadowed_indoor.jpg'/></td>
    </tr>
    <tr>
        <td align='center'>interreflection</td>
        <td align='center'>scene</td>
    </tr>
    <tr>
        <td align='center'><img src='./images/02_PRT_InterRef_indoor.jpg'/></td>
        <td align='center'><img src='./images/02_PRT_InterRef_indoor_scene.jpg'/></td>
    </tr>
</table>

<table border="0">
    <tr>
        <td align='center' colspan=2><b>SkyBox</b></td>
    </tr>
    <tr>
        <td align='center'>unshadowed</td>
        <td align='center'>shadowed</td>
    </tr>
    <tr>
        <td align='center'><img src='./images/02_PRT_Unshadowed_skybox.jpg'/></td>
        <td align='center'><img src='./images/02_PRT_Shadowed_skybox.jpg'/></td>
    </tr>
    <tr>
        <td align='center'>interreflection</td>
        <td align='center'>scene</td>
    </tr>
    <tr>
        <td align='center'><img src='./images/02_PRT_InterRef_skybox.jpg'/></td>
        <td align='center'><img src='./images/02_PRT_InterRef_skybox_scene.jpg'/></td>
    </tr>
</table>

<table border="0">
    <tr>
        <td align='center'><b>旋转</b></td>
    </tr>
    <tr>
        <td align='center'><img src='./images/02_PRT_InterRef_gracecathedral.gif'/></td>
    </tr>
</table>

# GAMES202 Lab3

## 完成内容

1. 实现直接光照
2. 实现 Screen Space Ray Tracing
3. 实现间接光照

# 1. 漫反射率

<table border="0">
    <tr>
        <td align='center'>漫反射率</td>
    </tr>
    <tr>
        <td align='center'><img src='./images/03_Diffuse0.jpg' width='100%' hight='100%'/></td>
    </tr>
    <tr>
        <td align='center'><img src='./images/03_Diffuse1.jpg' width='100%' hight='100%'/></td>
    </tr>
    <tr>
        <td align='center'><img src='./images/03_Diffuse2.jpg' width='100%' hight='100%'/></td>
    </tr>
</table>

## 2. 实现 Screen Space Ray Tracing

<table border="0">
    <tr>
        <td align='center'><img src='./images/03_RayTracing0.jpg' width='100%' hight='100%'/></td>
    </tr>
    <tr>
        <td align='center'><img src='./images/03_RayTracing1.jpg' width='100%' hight='100%'/></td>
    </tr>
</table>

## 3. 实现间接光照

<table border="0">
    <tr>
        <td align='center'>1 PSS</td>
    </tr>
    <tr>
        <td align='center'><img src='./images/03_1PSS.jpg' width='100%' hight='100%'/></td>
    </tr>
    <tr>
        <td align='center'>60 PSS</td>
    </tr>
    <tr>
        <td align='center'><img src='./images/03_60PSS.jpg' width='100%' hight='100%'/></td>
    </tr>
</table>

# GAMES202 Lab4

## 完成内容

1. 实现预计算E(μ)
2. 实现预计算Eavg
3. 正确实现PBR 材质
4. 正确实现Kulla-Conty 材质
5. Bonus 1：实现重要性采样的预计算方法
6. Bonus 2：在预计算E(μ) 时，使用Split Sum 完成预计算工作

## 1. 预计算E(μ)，2. 预计算Eavg

<table border="0">
    <tr>
        <td align='center'>预计算E(μ)</td>
        <td align='center'>预计算Eavg</td>
    </tr>
    <tr>
        <td align='center'><img src='./images/04_GGX_E_MC_LUT.jpg' width='100%' hight='100%'/></td>
        <td align='center'><img src='./images/04_GGX_Eavg_LUT_MC.jpg' width='100%' hight='100%'/></td>
    </tr>
</table>

## 3. 实现 PBR 材质

<table border="0">
    <tr>
        <td align='center'><img src='./images/04_PBR.jpg' width='100%' hight='100%'/></td>
    </tr>
</table>

## 4. 实现Kulla-Conty 材质

<table border="0">
    <tr>
        <td align='center'><img src='./images/04_Kulla-Conty.jpg' width='100%' hight='100%'/></td>
    </tr>
</table>

## 5. Bonus 1：实现重要性采样的预计算方法

<table border="0">
    <tr>
        <td align='center'>预计算E(μ)</td>
        <td align='center'>预计算Eavg</td>
    </tr>
    <tr>
        <td align='center'><img src='./images/04_GGX_E_LUT.jpg' width='100%' hight='100%'/></td>
        <td align='center'><img src='./images/04_GGX_Eavg_LUT.jpg' width='100%' hight='100%'/></td>
    </tr>
</table>

## 6. Bonus 2：在预计算E(μ) 时，使用Split Sum 完成预计算工作

<table border="0">
    <tr>
        <td align='center'><img src='./images/04_Split-Sum.jpg' width='50%' hight='50%'/></td>
    </tr>
</table>

# GAMES202 Lab5

<table border="0">
    <tr>
        <td align='center'><img src='./images/05_01.jpg' width='50%' hight='50%'/></td>
    </tr>
</table>
