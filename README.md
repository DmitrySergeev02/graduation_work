# Разработка модели автоматического построения графов знаний из текстовых источников
Модель основывается на методе Seq2Rel с использование методов предобработки текста (очистка текста и разрешение кореференциальных цепочек) и методов постобработки триплетов (фильтрация с помощью правил).  
В данном репозитории представлены ipynb файлы, с помощью которых можно ознакомиться с работой.  
* В блокноте data_prepare.ipynb представлен процесс скачивания новостных статей и их предобработки до передачи модели.  
* В блокноте triple_extraction.ipynb представлен процесс использования метода Seq2Rel для извлечения триплетов из текста.  
* В блокноте triple_filtration.ipynb представлен процесс фильтрации и коррекции триплетов


В случае возникновения проблем с представлением блокнотов на github, ниже представлены ссылки на эти блокноты в Google Colab:
* data_prepare.ipynb - [data_prepare](https://colab.research.google.com/drive/1fg2a1DRULwghGi9B5jxT9KfE5CkgYoHc?usp=sharing)
* triple_extraction.ipynb - [data_extraction](https://colab.research.google.com/drive/1N3_8coil3EC4Egk811vsiqj_Oxm0uSop?usp=sharing)
* triple_filtration.ipynb - [triple_filtration](https://colab.research.google.com/drive/1Qq-AA1ljJ9PuVArBfwcjgR8cJFOnycAh?usp=sharing)
