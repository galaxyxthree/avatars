# How to personalize your shield with company logo

- To be able to create you own shield you must first head to [Shields.io] and select the type of shield you need.
- To test out a simple one head to _activity_ followed by the correct sub specification such as the _GitHub_ Specification
- CLick the link provided and then head to your GitHub Repository which you want to use 
- Copi and paste the end _Repo_ which will be in the URL when you are inside your repo
- Then provide the username which you have on your profile, this will generate a shield under which should state _last-commit_ followed by _Today_ or another day of whicever date you have last committed to that specific Repo
- You may after change colors or edit the type of shield used

-----

### Formatting your logo in the Shield format

- head to your VS code or whichever terminal you utilize to write in your markdown (.md) format

```sh

 This should be what is available to you:
 
 ![Github Last-commit](Url provided by shield.io)

```

- After such insertion now head to the following website: [Base64]
- The format of the image must be a _Base64_
- The website will ask you to upload your immage, remember that you will get you Base64 code for the image provided
- the image should be between 14Pxl x 14pxl and 32pxl x 32 pxl 
- Remember that the image does not have to be commkitted to your Github through .png or any file with a commit to the repo, the image will be converted from the _Base64_ formmat

```sh

Now take the Base64 and added in the following way by adding the following right next to the _Url provided by shield.io_

&logo=data:image/png;base64,(the codes provided to you from the base 64 app)

```
```sh

Now your link should look like the following 

![Github Last-commit](https://img.shields.io/github/last-commit/galaxyxthree/galaxyx_web_applications?color=ff0&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAE8AAAAyCAYAAAAdiIaZAAAACXBIWXMAAD2DAAA9gwGH6AkLAAADBklEQVRoge2b0ZGbQAyGdZ57Pzq47eDoIHQQdxCX4A7OJTgVhBJIBeE6sDvgOiAVbIYbkWF2YPUb6TAk+83sE7bwil30Sys/eO8JoCCiIxFlwUfPRFQhBm6kCD7e8LAk49/vAps1EZ2g+3TOE0bh4xSADXTk3vtm4m5Hw/t04xKZ1RmxgdykFJxXGU6oFu6VG91HWhAesbMDFme4rEPCrazhi/DdcDvfFcR5a8LyQanZmvNWhYXzVrUaQHILIxbOeyGig4Gdjqtw3UIWZSy71DxaGCGiH/wy12qxVri+56Ghe9DPShsfICK5BqLgv8iDNKcUMBQk5ylIzlOQnKfAKtoivI9EY20gCm1mLJ2WAUiAz0ASLVFO2O4S/dbYJpL0I5hUVZxigj1ZxP5phr3mkx84VJJCtm0zKIYOKyzoFnkTxG+nI19v3GaSGJfE9pBr8PmShwj6zrtMpGAHzi62yJWzldlZkTbalryytshJm05aSBXrs4WlUBcZtM7LDBL1e6GuSmucV/C2fbq7G+ZRaR2IOu/A29MPxi8i+vpJE1uCJ56DD0aJFniRaFtsOKLO4RtLMnFVIivPqkq8JaC00eLo8b8lVVUUJOcpQJynFcHStp/zWljFcSfiPK0SfxaE9JxjwJdINMwMghyUcvanZ/0Nh0+0Yce1nAcelYL4e/AgHNucW7z8zS1itaFNYsfted75yIOvuFBCUkHyEqnFOe6Q2iqt0B53kOp9SAuZ1Bc31U+3dqS+Qgm3M2ghgwqHK6SO/CQk53VJqihIzlOQnKdgBxyWSNe3WEmWWtkugI1GkiqtcGxIfD3WWb5G9srz6g+p0otkN6LKW46kyDHemMjucVwjQ3kbiYSOxSoq0q+RzKgCVxbxnEI10vxVGEat+dLIwdU31QVwS3dBzIbpWMp5iBj3wCsC6QRwS81pyWgrBRaps4DAV8hiASxJFQXJeQqS8xQs6TxJHiDvKqkw+/OG36NnwWgbi7ixuiEacRvDf0VCA/2zsiWd6Bz7g/AtWNjQQUR/ANFHHfUFYGE8AAAAAElFTkSuQmCC)


```

- Remember that the best format for the logo is not to have any background but to have it transaparent from the file, that way it will directly be the logo instead of being shrinked.

```sh

You may make the shield a hyperlink by adding the following:

These brakets around the previous line []
as well as the URL it will be hyperlinked with enclosed by these brakets ()

```

```sh

Now your link should look like the following 

[![Github Last-commit](https://img.shields.io/github/last-commit/galaxyxthree/galaxyx_web_applications?color=ff0&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAE8AAAAyCAYAAAAdiIaZAAAACXBIWXMAAD2DAAA9gwGH6AkLAAADBklEQVRoge2b0ZGbQAyGdZ57Pzq47eDoIHQQdxCX4A7OJTgVhBJIBeE6sDvgOiAVbIYbkWF2YPUb6TAk+83sE7bwil30Sys/eO8JoCCiIxFlwUfPRFQhBm6kCD7e8LAk49/vAps1EZ2g+3TOE0bh4xSADXTk3vtm4m5Hw/t04xKZ1RmxgdykFJxXGU6oFu6VG91HWhAesbMDFme4rEPCrazhi/DdcDvfFcR5a8LyQanZmvNWhYXzVrUaQHILIxbOeyGig4Gdjqtw3UIWZSy71DxaGCGiH/wy12qxVri+56Ghe9DPShsfICK5BqLgv8iDNKcUMBQk5ylIzlOQnKfAKtoivI9EY20gCm1mLJ2WAUiAz0ASLVFO2O4S/dbYJpL0I5hUVZxigj1ZxP5phr3mkx84VJJCtm0zKIYOKyzoFnkTxG+nI19v3GaSGJfE9pBr8PmShwj6zrtMpGAHzi62yJWzldlZkTbalryytshJm05aSBXrs4WlUBcZtM7LDBL1e6GuSmucV/C2fbq7G+ZRaR2IOu/A29MPxi8i+vpJE1uCJ56DD0aJFniRaFtsOKLO4RtLMnFVIivPqkq8JaC00eLo8b8lVVUUJOcpQJynFcHStp/zWljFcSfiPK0SfxaE9JxjwJdINMwMghyUcvanZ/0Nh0+0Yce1nAcelYL4e/AgHNucW7z8zS1itaFNYsfted75yIOvuFBCUkHyEqnFOe6Q2iqt0B53kOp9SAuZ1Bc31U+3dqS+Qgm3M2ghgwqHK6SO/CQk53VJqihIzlOQnKdgBxyWSNe3WEmWWtkugI1GkiqtcGxIfD3WWb5G9srz6g+p0otkN6LKW46kyDHemMjucVwjQ3kbiYSOxSoq0q+RzKgCVxbxnEI10vxVGEat+dLIwdU31QVwS3dBzIbpWMp5iBj3wCsC6QRwS81pyWgrBRaps4DAV8hiASxJFQXJeQqS8xQs6TxJHiDvKqkw+/OG36NnwWgbi7ixuiEacRvDf0VCA/2zsiWd6Bz7g/AtWNjQQUR/ANFHHfUFYGE8AAAAAElFTkSuQmCC)] (URL needed here)

```

This is how it should look like without the link:

![Github Last-commit](https://img.shields.io/github/last-commit/galaxyxthree/galaxyx_web_applications?color=ff0&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAE8AAAAyCAYAAAAdiIaZAAAACXBIWXMAAD2DAAA9gwGH6AkLAAADBklEQVRoge2b0ZGbQAyGdZ57Pzq47eDoIHQQdxCX4A7OJTgVhBJIBeE6sDvgOiAVbIYbkWF2YPUb6TAk+83sE7bwil30Sys/eO8JoCCiIxFlwUfPRFQhBm6kCD7e8LAk49/vAps1EZ2g+3TOE0bh4xSADXTk3vtm4m5Hw/t04xKZ1RmxgdykFJxXGU6oFu6VG91HWhAesbMDFme4rEPCrazhi/DdcDvfFcR5a8LyQanZmvNWhYXzVrUaQHILIxbOeyGig4Gdjqtw3UIWZSy71DxaGCGiH/wy12qxVri+56Ghe9DPShsfICK5BqLgv8iDNKcUMBQk5ylIzlOQnKfAKtoivI9EY20gCm1mLJ2WAUiAz0ASLVFO2O4S/dbYJpL0I5hUVZxigj1ZxP5phr3mkx84VJJCtm0zKIYOKyzoFnkTxG+nI19v3GaSGJfE9pBr8PmShwj6zrtMpGAHzi62yJWzldlZkTbalryytshJm05aSBXrs4WlUBcZtM7LDBL1e6GuSmucV/C2fbq7G+ZRaR2IOu/A29MPxi8i+vpJE1uCJ56DD0aJFniRaFtsOKLO4RtLMnFVIivPqkq8JaC00eLo8b8lVVUUJOcpQJynFcHStp/zWljFcSfiPK0SfxaE9JxjwJdINMwMghyUcvanZ/0Nh0+0Yce1nAcelYL4e/AgHNucW7z8zS1itaFNYsfted75yIOvuFBCUkHyEqnFOe6Q2iqt0B53kOp9SAuZ1Bc31U+3dqS+Qgm3M2ghgwqHK6SO/CQk53VJqihIzlOQnKdgBxyWSNe3WEmWWtkugI1GkiqtcGxIfD3WWb5G9srz6g+p0otkN6LKW46kyDHemMjucVwjQ3kbiYSOxSoq0q+RzKgCVxbxnEI10vxVGEat+dLIwdU31QVwS3dBzIbpWMp5iBj3wCsC6QRwS81pyWgrBRaps4DAV8hiASxJFQXJeQqS8xQs6TxJHiDvKqkw+/OG36NnwWgbi7ixuiEacRvDf0VCA/2zsiWd6Bz7g/AtWNjQQUR/ANFHHfUFYGE8AAAAAElFTkSuQmCC)

This is how it should look like with the link to our Github:

[![Github Last-commit](https://img.shields.io/github/last-commit/galaxyxthree/galaxyx_web_applications?color=ff0&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAE8AAAAyCAYAAAAdiIaZAAAACXBIWXMAAD2DAAA9gwGH6AkLAAADBklEQVRoge2b0ZGbQAyGdZ57Pzq47eDoIHQQdxCX4A7OJTgVhBJIBeE6sDvgOiAVbIYbkWF2YPUb6TAk+83sE7bwil30Sys/eO8JoCCiIxFlwUfPRFQhBm6kCD7e8LAk49/vAps1EZ2g+3TOE0bh4xSADXTk3vtm4m5Hw/t04xKZ1RmxgdykFJxXGU6oFu6VG91HWhAesbMDFme4rEPCrazhi/DdcDvfFcR5a8LyQanZmvNWhYXzVrUaQHILIxbOeyGig4Gdjqtw3UIWZSy71DxaGCGiH/wy12qxVri+56Ghe9DPShsfICK5BqLgv8iDNKcUMBQk5ylIzlOQnKfAKtoivI9EY20gCm1mLJ2WAUiAz0ASLVFO2O4S/dbYJpL0I5hUVZxigj1ZxP5phr3mkx84VJJCtm0zKIYOKyzoFnkTxG+nI19v3GaSGJfE9pBr8PmShwj6zrtMpGAHzi62yJWzldlZkTbalryytshJm05aSBXrs4WlUBcZtM7LDBL1e6GuSmucV/C2fbq7G+ZRaR2IOu/A29MPxi8i+vpJE1uCJ56DD0aJFniRaFtsOKLO4RtLMnFVIivPqkq8JaC00eLo8b8lVVUUJOcpQJynFcHStp/zWljFcSfiPK0SfxaE9JxjwJdINMwMghyUcvanZ/0Nh0+0Yce1nAcelYL4e/AgHNucW7z8zS1itaFNYsfted75yIOvuFBCUkHyEqnFOe6Q2iqt0B53kOp9SAuZ1Bc31U+3dqS+Qgm3M2ghgwqHK6SO/CQk53VJqihIzlOQnKdgBxyWSNe3WEmWWtkugI1GkiqtcGxIfD3WWb5G9srz6g+p0otkN6LKW46kyDHemMjucVwjQ3kbiYSOxSoq0q+RzKgCVxbxnEI10vxVGEat+dLIwdU31QVwS3dBzIbpWMp5iBj3wCsC6QRwS81pyWgrBRaps4DAV8hiASxJFQXJeQqS8xQs6TxJHiDvKqkw+/OG36NnwWgbi7ixuiEacRvDf0VCA/2zsiWd6Bz7g/AtWNjQQUR/ANFHHfUFYGE8AAAAAElFTkSuQmCC)](https://github.com/galaxyxthree?tab=repositories)



-----

Hope this helped :smile:



[Shields.io]:https://shields.io/
[Base64]:https://www.w3docs.com/tools/image-base64