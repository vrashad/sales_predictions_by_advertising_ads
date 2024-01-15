# Tarixi məlumatlara əsaslanaraq, reklamin tipindən və sayına uyğun olaraq, satış proqnozunu verən proyekt
Bu model şirkətlərə reklam xərclərinə, müştəri seqmentinə və marketinq platformaları kimi amillərə əsaslanan gələcək satışları proqnozlaşdırmağa imkan verir. 

Modeli tərtib etmək üçün sadəcə olaraq **satis_proqnozlari.ipynb** Jupyter Notebook faylını ya local olaraq ya da Google Colab kimi Cloud servislərinin birində açırıq

Tarixi məlumatlar **tarixi_məlumatlar.csv** faylındadır

İlk olaraq fayldakı məlumatları emal edirik və onları normallaşdırırıq.

Sonra məlumatları vizuallaşdıraraq, satış həcminin daha çox hansı reklam tipindən asılı olduğunu müəyyənləşdiririk

<img src="https://i.postimg.cc/Y9zFJ0DY/1.png" />

Gördüyümüz kimi satış həcmi daha çox TV reklam tipindən asılıdır. 

Daha az asılılıq Qəzetdə yeləşdirilən reklamladır

Bunu nəzərə alaraq, reklam büdcəsini daha çox TV reklamına ayıraraq satış həcmini artıra bilərik

Bunu yoxlamaq üçün satış proqnozunu verən modeli tərtib etməliyik

Model tərtib ediləndən sonra artıq reklamın tipindən və sayından asılı olaraq, satışın proqnozlaşdırılan həcminini əlsə edirik

<img src="https://i.postimg.cc/X7QRngBD/2.png" />
