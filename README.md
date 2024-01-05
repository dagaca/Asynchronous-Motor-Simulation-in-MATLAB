# Asynchronous-Motor-Simulation-in-MATLAB

## Genel Bakış

Bu repo, "RESEARCH OF THE DIRECT TORQUE CONTROL SYSTEM BY INDUCTION MOTOR" başlıklı makaleden elde edilen parametrelerle 2 çift kutuplu bir asenkron motorun simülasyonunu içermektedir. Simülasyon, 2 çift kutuplu bir asenkron motorun boşta çalışma koşullarını modellemektedir.
MATLAB Simulink projesi MATLAB R2017b sürümü kullanılarak oluşturulmuştur.

## Asenkron Motor Simulink Modeli

![simulink_gorsel](https://github.com/dagaca/Asynchronous-Motor-Simulation-in-MATLAB/assets/80363244/190ef337-a192-4193-a6f1-51a838c93455)



**Asenkron Motor parametreleri aşağıdaki gibidir:**

![motor_parameters](https://github.com/dagaca/Asynchronous-Motor-Model-in-MATLAB/assets/80363244/8023029f-4f8e-464a-add3-d09c61129fb4)


- Frictional loss = 11W, Windage loss = 11W, Toplam kayıp = 22W
- Wn = (2*pi*1450) / 60 = 151.84 rad/s
- 22 / 151.84 = 0.14489 Nm
- Friction factor = 0.0009542 F(N.m.s)

Diğer parametreler kaynak makaleden alınmıştır.


## Grafikler
### Hız Grafiği

![hız](https://github.com/dagaca/Asynchronous-Motor-Simulation-in-MATLAB/assets/80363244/9158ee1d-6f7d-4249-bfb0-f8f0bd0b3575)



### Tork Grafiği

![tork](https://github.com/dagaca/Asynchronous-Motor-Simulation-in-MATLAB/assets/80363244/1770cb08-ca22-4e51-b99c-6c87651f6ebf)



### Stator Akımları Grafiği

![statorakımları](https://github.com/dagaca/Asynchronous-Motor-Simulation-in-MATLAB/assets/80363244/5d83480e-f332-4b73-adca-02c6d32b175b)



### Rotor Akımları Grafiği

![rotorakımları](https://github.com/dagaca/Asynchronous-Motor-Simulation-in-MATLAB/assets/80363244/7219b3fe-a2eb-45d9-812e-8d1ac82b63b1)



### Stator Voltajı Grafiği

![statorvoltajı](https://github.com/dagaca/Asynchronous-Motor-Simulation-in-MATLAB/assets/80363244/4361330f-5c5e-40f0-9232-f56944dde93e)



### Rotor Voltajı Grafiği

![rotorvoltajı](https://github.com/dagaca/Asynchronous-Motor-Simulation-in-MATLAB/assets/80363244/1e631b40-aed2-4857-ab82-4cd3ddc06d30)



## Referanslar
Alzubaydy, A. I. J., Dorohobid, V. P., Hasan, M. S., & Borozdin, M. K. (2018). RESEARCH OF THE DIRECT TORQUE CONTROL SYSTEM BY INDUCTION MOTOR. Системи Управління, Навігації Та Зв’язку. Збірник Наукових Праць, 2(48), 3–8. https://doi.org/10.26906/sunz.2018.2.003 


## Nasıl Başlamalı?

1. Bu repo'yu bilgisayarınıza klonlayın.
   ```bash
   git clone https://github.com/dagaca/Asynchronous-Motor-Simulation-in-MATLAB.git
