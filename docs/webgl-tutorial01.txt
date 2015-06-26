###################################
WebGL Tutorial 01: 
###################################

Nada ainda

$$x = \\sum_{i}^{N}{x^i}$$

.. image:: imagem.jpg


.. code-block:: python
   :linenos:

   imagem = cv2.imread('imagem.jpg')
   imagemlab = cv2.cvtColor(imagem, cv2.COLOR_BGR2LAB)
   histlab = cv2.calcHist([imagemlab], [1,2], None, [256,256],[0,256,0,256])
   cv2.imshow('resultado',imagemlab)
   cv2.waitKey()

