# Invert-PDF-Colors
Reverse PDF background color from white to black in Chrome

If you fall in love with dark mode.However, you have to read a lot of PDF files every single day and light background makes you uncomfortable.You have came right place

Now , let us go into detail.(〃￣︶￣)人(￣︶￣〃)

1.Right-click on the PDF document which you want to open.

2.Go to Open with > Google Chrome.

3.Press SHIFT + CTRL + I to open the console.

4.Make sure that you’re on the Console tab.

5.Copy the following code and paste it into the console and hit Enter:


          var cover = document.createElement("div");

          let css = `

                    position: fixed;

                    pointer-events: none;

                    top: 0;

                    left: 0;

                    width: 100vw;

                    height: 100vh;

                    background-color: white;

                    mix-blend-mode: difference;

                    z-index: 1;

                    `

          cover.setAttribute("style", css);

          document.body.appendChild(cover);

Don't worry , this effect is not permanent if you close your browser.

The modifications DISAPPEAR as soon as you close the browser or tab.`(*>﹏<*)′

Here it the result

Before :

![chrome_FnMeqJ6xQ5](https://user-images.githubusercontent.com/58034430/120745275-01d40280-c527-11eb-9cd4-a1431b5d9bde.png)

After : 

![chrome_tamrsvF38n](https://user-images.githubusercontent.com/58034430/120745335-23cd8500-c527-11eb-8af7-14f9b050d37e.png)

I don't know you and you don't know me. Probably we are not even living in the same country. We look different. We speak different languages. Maybe we are from entirely different generations. We are just complete strangers. 

But there is something that connects us. We both have great taste in getting programming 

Thank you for being here. God bless you, whoever you are
