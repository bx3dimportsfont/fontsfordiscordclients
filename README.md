So to use this follow this guide or watch the youtube video. 


1. step
what you are going to need to do is look at the font you want in the github repo.

2. step
now you will see the font file right click view raw and press copy link address.

3. step
now go to https://raw.githack.com add paste the link that you copied. and press the copy button under "use this url for development

4. step
now go to discord with the client you have. and go to edit quickcss

5. step
paste this in the quickcss window

@font-face {
    font-family: 'MyCustomDaFont';
    src: url('import link from githack here') format('woff2');
}

*, ::placeholder, body, button, input, select, textarea {
    font-family: 'MyCustomDaFont', sans-serif !important;
}

6. step
now that you have done that, remove the "import link from githack here" DO NOT REMOVE THE '' IT WILL RUIN IT

7. step
now you can close out of the vencord quickcss editor. have fun with your font! 
