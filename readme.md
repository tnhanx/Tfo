# **Tfo**
A website for two-point filestorage online (tfo) (20221017). 

![Tfo's Logo](./readme/tfo.logo.svg)

## Features

1. Move the **operation (setting/login/text-editing/download) button to bottom left corner**

![Operation Button](./readme/button.png)

2. Add random color of the directory div and more-disk div

3. Change buttons into outline style

4. Resize the Preview div

... and more

> Specifically, you could clone or fork the repo and modify your theme. The theme is based on classic.html for a fresh look, all original features are supported via updates. The theme will realize many functions, you could keep looking forward to next updates. However, the private content related to other platforms, such as comments system, webmaster tools, access statistics, poetry div, which are not included in the theme. If you need, you could add them in the setup page by your own. The PHP historical version of the theme can be found in the <a href="./theme/" title="Old Theme">Theme</a> folder.

## Modified Files

<table> 
    <tbody>
        <tr> 
            <th>Type</th> 
            <th>Files</th> 
            <th>Postscript</th> 
        </tr> 
        <tr> 
            <td rowspan="4">Information</td> 
            <td>
                <a href="./app.json" title="app.json">app.json</a>
            </td>
            <td rowspan="4">Tfo's information is described in these files for deployment</td> 
        </tr>
        <tr>
            <td>
                <a href="./readme.md" title="readme.md">readme.md</a>
            </td>
        </tr>
        <tr>
            <td>
                <a href="./common.php" title="common.php">common.php</a>
            </td>
        </tr>
        <tr>
            <td>
                <a href="./conststr.php" title="conststr.php">conststr.php</a>
            </td>
        </tr>
        <tr> 
            <td rowspan="11">UpdateAddress</td> 
            <td>
                <a href="./platform/AliyunFC.php" title="AliyunFC.php">AliyunFC.php</a>
            </td>
            <td rowspan="11">Address to update is changed for easy management and updating</td> 
        </tr>
        <tr> 
            <td>
                <a href="./platform/BaiduCFC.php" title="BaiduCFC.php">BaiduCFC.php</a>
            </td> 
        </tr>
        <tr> 
            <td>
                <a href="./platform/Heroku.php" title="Heroku.php">Heroku.php</a>
            </td> 
        </tr>
        <tr>
            <td>
                <a href="./platform/HuaweiFG_env.php" title="HuaweiFG_env.php">HuaweiFG_env.php</a>
            </td>
        </tr>
        <tr>
            <td>
                <a href="./platform/HuaweiFG_file.php" title="HuaweiFG_file.php">HuaweiFG_file.php</a>
            </td>
        </tr>
        <tr>
            <td>
                <a href="./platform/Normal.php" title="Normal.php">Normal.php</a>
            </td>
        </tr>
        <tr> 
            <td>
                <a href="./platform/Replit.php" title="Replit.php">Replit.php</a>
            </td> 
        </tr>
        <tr>
            <td>
                <a href="./platform/TencentSCF_env.php" title="TencentSCF_env.php">TencentSCF_env.php</a>
            </td>
        </tr>
        <tr>
            <td>
                <a href="./platform/TencentSCF_file.php" title="TencentSCF_file.php">TencentSCF_file.php</a>
            </td>
        </tr>
        <tr>
            <td>
                <a href="./platform/Vercel_env.php" title="Vercel_env.php">Vercel_env.php</a>
            </td>
        </tr>
        <tr>
            <td>
                <a href="./platform/Vercel.php" title="Vercel.php">Vercel.php</a>
            </td>
        </tr>
        <tr> 
            <td rowspan="1">Theme</td> 
            <td>
                <a href="./theme/tfo.html" title="tfo.html">tfo.html</a>
            </td>
            <td rowspan="1">Tfo's theme for OneManager-php</td> 
        </tr>
    </tbody>
</table>

## To Do

- [ ] Support markdown file in textbundle folder as a readme
- [ ] Support list iterms as icons

... and more.

## Deploy and More Information

See [Original Readme](./readme_original.md) | [原始简体中文 Readme](./readme_original_cn.md)

If you want to deploy Tfo's repo, you can change the default fields to this repo address directly.