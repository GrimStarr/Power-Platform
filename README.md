# PowerBI Лицензийн тухай 

Бидний өмнө нь ашигладаг байсан тохиргоо нь лицензийн өөрчлөлтөөс болоод ашиглах боломжгүй болсон байна.
 
Гэхдээ PowerBI нь угсарсан дашбордоо веб линк үүсгэн public тохиргоотой хуваалцаж болдог. Уг линкийг ашиглан PowerApps дээрээ лицензгүй хэрэглэгчид тухайн дашбордыг үзэж болно.

Ажиллагааны дараалал:

1.  PowerBI дашбордоо вебсайт хэлбэрээр хуваалцана.

     ![components icon.](media/webshare.png "Components icon")

2.  Үүссэн [линкийг]([/power-virtual-agents/publication-connect-bot-to-web-channels#custom-website](https://app.powerbi.com/view?r=eyJrIjoiNGI0YTE3ZmEtOGYyYy00OGYwLTg0NjgtNTQwNTcxMTZkZGFkIiwidCI6IjJlNjIyMWI2LTkzN2EtNDQ5Yi05YTNmLWIzMjI3MzMxYzM3ZCIsImMiOjEwfQ%3D%3D)) хуулна

3.  Select an editable element on the canvas.

4.  Select **Components** ![components icon.](media/webshare.png "Components icon") from the left side of the screen.  

5.  Under **Portal components**, select **IFrame**. The IFrame placeholder is added to the canvas.

6.  In the properties pane on the right side of the screen, enter the following information:

    - **Width**: Enter the width of the IFrame.

    - **Height**: Enter the height of the IFrame.

        > [!NOTE]
        > You can also select the IFrame on the canvas and drag the handles to resize it.

    - **Link**: Enter the URL of the website to be displayed in the IFrame. Only secured links are accepted—that is, https:// is mandatory. By default, <https://www.bing.com> is available as the value.
    
        > [!div class=mx-imgBorder]
        > ![IFrame properties.](media/iframe-props.png "IFrame properties")  

> [!NOTE]
> You can also add [Power Virtual Agent](/power-virtual-agents/fundamentals-what-is-power-virtual-agents) bot to the  IFrame similarly using steps described in [add bot to your web site](/power-virtual-agents/publication-connect-bot-to-web-channels#custom-website).

### See also

- [Power Apps portals Studio](portal-designer-anatomy.md)
- [Create and manage webpages](create-manage-webpages.md)
- [WYSIWYG editor](compose-page.md)


[!INCLUDE[footer-include](../../includes/footer-banner.md)]
