# Asynchronous-Motor-Model-in-MATLAB
Bu MATLAB Simulink projesi, "RESEARCH OF THE DIRECT TORQUE CONTROL SYSTEM BY INDUCTION MOTOR" başlıklı makaleden elde edilen parametrelerle 2 çift kutuplu bir asenkron motorun simülasyonunu içermektedir. Motor boşta çalışma koşullarında simüle edilmiştir.


## Motor Simulink Modeli

![simulink_gorsel](https://github.com/dagaca/Asynchronous-Motor-Model-in-MATLAB/assets/80363244/2404f001-978b-42e8-b530-6bd10e4de260)



**Motor parametreleri aşağıdaki gibidir:**

![motor_parameters](https://github.com/dagaca/Asynchronous-Motor-Model-in-MATLAB/assets/80363244/8023029f-4f8e-464a-add3-d09c61129fb4)



- Frictional loss = 11W, Windage loss = 11W, Toplam kayıp = 22W
- Wn = (2*pi*1450) / 60 = 151.84 rad/s
- 22 / 151.84 = 0.14489 Nm
- Friction factor = 0.0009542 F(N.m.s)

Diğer parametreler kaynak makaleden alınmıştır.




## Grafikler
### Hız Grafiği

![hızgrafiği](https://github.com/dagaca/Asynchronous-Motor-Model-in-MATLAB/assets/80363244/a29e1fdc-12b1-435b-b85b-b493f4884b27)




### Tork Grafiği

![torkgrafiği](https://github.com/dagaca/Asynchronous-Motor-Model-in-MATLAB/assets/80363244/7ec56c90-dc5f-4c0e-a9cf-bd5df7d49327)




### Stator Akımları Grafiği

![statorakımlarıgrafiği](https://github.com/dagaca/Asynchronous-Motor-Model-in-MATLAB/assets/80363244/b35c9eff-3790-4017-93c1-7822ade38a9e)




### Rotor Akımları Grafiği

![rotorakımlarıgrafiği](https://github.com/dagaca/Asynchronous-Motor-Model-in-MATLAB/assets/80363244/4ad2e0b4-469b-4ea0-9310-0c11ec31a0ef)




### Stator Voltajı Grafiği

![statorvoltajı](https://github.com/dagaca/Asynchronous-Motor-Model-in-MATLAB/assets/80363244/8a1598ba-83f9-4e5a-9231-d1d88080b783)




### Rotor Voltajı Grafiği

![rotorvoltajı](https://github.com/dagaca/Asynchronous-Motor-Model-in-MATLAB/assets/80363244/cd08d8a6-4bba-44a9-927a-3dfa47180098)





## Referanslar
Alzubaydy, A. I. J., Dorohobid, V. P., Hasan, M. S., & Borozdin, M. K. (2018). RESEARCH OF THE DIRECT TORQUE CONTROL SYSTEM BY INDUCTION MOTOR. Системи Управління, Навігації Та Зв’язку. Збірник Наукових Праць, 2(48), 3–8. https://doi.org/10.26906/sunz.2018.2.003 
