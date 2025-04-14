# Lab06_VisaoComputacional

## Imagens

### Girafa
Código: Girafa.py <br>

- Procedimentos:

	1.	Conversão para RGB: A imagem é convertida de BGR para RGB para correta visualização.
	2.	Conversão para escala de cinza (Gray Scale): A imagem RGB é transformada em tons de cinza para facilitar o processamento.
	3.	Binarização com threshold inverso: A imagem em tons de cinza é convertida para preto e branco usando um limiar ajustado automaticamente. Regiões claras viram pretas e vice-versa.
	4.	Aplicação de gradiente morfológico: Utiliza uma operação morfológica para realçar as bordas dos objetos presentes na imagem binária.

![image](https://github.com/user-attachments/assets/2814fbae-a809-4b07-ba14-db27629e61c0)
<img width="375" alt="image" src="https://github.com/user-attachments/assets/8c10df50-a503-43e2-805f-466ff5f2df28" />

### Avião
Código: Aviao.py <br>

- Procedimentos:

	1.	Conversão para RGB:	A imagem é convertida de BGR para RGB para correta visualização com Matplotlib.
	2.	Conversão para escala de cinza (Gray Scale): A imagem RGB é transformada em tons de cinza para facilitar o processamento.
	3.	Binarização com threshold truncado: É aplicado um limiar (threshold) com a técnica THRESH_TRUNC, que limita os pixels acima do limiar a um valor fixo, preservando os tons mais escuros.
	4.	Aplicação de blur (suavização): É usado o filtro de média (cv2.blur) para suavizar a imagem e reduzir o ruído, preparando para a detecção de bordas.
	5.	Detecção de bordas com Canny: As bordas da imagem suavizada são detectadas com o algoritmo de Canny, utilizando limiares baseados na intensidade média da imagem.


![image](https://github.com/user-attachments/assets/379f41f0-2190-41cc-ad8b-c067f2a4d2dd) <br>
![image](https://github.com/user-attachments/assets/2044f273-86c1-4655-8234-2bcad83334cf) <br>
