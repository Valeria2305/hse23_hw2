# hse23_hw2
- В качестве варианта задания мной были выбраны следующие данные:<br />
Клеточная линия: MCF-7, гистоновая метка: H3K36me3 <br />
## Ссылка на gooole-colab: <br />
https://colab.research.google.com/drive/1Kmkh4VCktCjt-kpCz_0POktOhtaAnEHZ#scrollTo=n22U0pjjcydg

## Сравнение FastQC:

- ENCFF389PKW до подрезания:<br />

<img width="383" alt="image" src="https://user-images.githubusercontent.com/77625525/222005748-f18d891a-d48b-4342-8b57-fad99c2fe579.png">
<img width="488" alt="image" src="https://user-images.githubusercontent.com/77625525/222005966-809f4255-44ce-475b-9c59-6d6c46f00f24.png">

- ENCFF082PFU до подрезания:<br />

<img width="380" alt="image" src="https://user-images.githubusercontent.com/77625525/222006577-d2a2fcfd-8dbd-46fc-b2b2-0fc466b3fd18.png">
<img width="518" alt="image" src="https://user-images.githubusercontent.com/77625525/222006613-90df8593-1f44-412c-9dc6-87e0d93237cf.png">

- ENCFF318ZNB до подрезания:<br />

<img width="384" alt="image" src="https://user-images.githubusercontent.com/77625525/222006715-26cfd9fb-d977-4ba5-bcc9-d2f32c114bac.png">
<img width="495" alt="image" src="https://user-images.githubusercontent.com/77625525/222006757-f500d12d-3abd-4f1a-b12d-30a8664b5400.png">

- ENCFF389PKW после подрезания:<br />

<img width="389" alt="image" src="https://user-images.githubusercontent.com/77625525/222006838-6ed1c171-d7e1-416e-828b-16edf72b9d11.png">
<img width="511" alt="image" src="https://user-images.githubusercontent.com/77625525/222006870-8e940f83-8566-41f3-bc64-8a3c3ea1f7da.png">

- ENCFF082PFU после подрезания:<br />

<img width="382" alt="image" src="https://user-images.githubusercontent.com/77625525/222006941-a3f20957-3730-4889-892a-156476cba4c4.png">
<img width="506" alt="image" src="https://user-images.githubusercontent.com/77625525/222006969-e17ea734-a845-465e-affc-02e271402b37.png">

- ENCFF318ZNB после подрезания:<br />

<img width="383" alt="image" src="https://user-images.githubusercontent.com/77625525/222007043-586c0b47-d433-40c5-a27f-1138ce99a7b4.png">
<img width="473" alt="image" src="https://user-images.githubusercontent.com/77625525/222007066-f11c6409-ff0a-42e9-804f-8d196075537f.png">

Изначальное качество ENCFF082PFU было лучше (например из per title sequence quality), однако после подрезания стало не особо хуже. Качество ENCFF389PKW практически не изменилось. Качество ENCFF318ZNB улучшилось.<br />

## Статистика по выравниваниям:<br />

<img width="880" alt="image" src="https://user-images.githubusercontent.com/77625525/222009467-a5d89c7c-4a32-4913-ad4d-9dcd372210c3.png">
Процент выравниваний достаточно низкий, потому что выравнивание происходило на одну хромосому, которая не может определять большую часть генома.<br />

## Диаграммы Эйлера-Венна:<br />

- Пересечение пиков 1 реплики и ENCODE:<br />

<img width="631" alt="image" src="https://user-images.githubusercontent.com/77625525/222009752-848f5542-f0d6-4fbc-ae8e-3d708dc2a04c.png">
<img width="560" alt="image" src="https://user-images.githubusercontent.com/77625525/222009789-83f01468-2a9b-4f0b-bfe1-8c04810e62d6.png">

- Пересечение пиков 2 реплики и ENCODE:<br />





