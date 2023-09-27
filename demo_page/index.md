## Enrollment-stage Backdoor Attacks on Speaker Recognition Systems via Adversarial Ultrasound

 - Automatic Speaker Recognition Systems (SRSs) have been widely used in voice applications for personal identification and access control. A typical SRS consists of three stages, i.e., training, enrollment, and recognition. Previous work has revealed that SRSs can be bypassed by backdoor attacks at the training stage or by adversarial example attacks at the recognition stage. In this paper, we propose TUNER, a new type of backdoor attack against the enrollment stage of SRS via adversarial ultrasound modulation, which is inaudible, synchronization-free, content-independent, and black-box. Our key idea is to first inject the backdoor into the SRS with modulated ultrasound when a legitimate user initiates the enrollment, and afterward, the polluted SRS will grant access to both the legitimate user and the adversary with high confidence. Our attack faces a major challenge of unpredictable user articulation at the enrollment stage. To overcome this challenge, we generate the ultrasonic backdoor by augmenting the optimization process with random speech content, vocalizing time, and volume of the user. Furthermore, to achieve real-world robustness, we improve the ultrasonic signal over traditional methods using sparse frequency points, pre-compensation, and single-sideband (SSB) modulation. We extensively evaluate TUNER on two common datasets and seven representative SRS models, as well as its robustness against seven kinds of defenses. Results show that our attack can successfully bypass speaker recognition systems while remaining effective to various speakers, speech content, etc. To mitigate this newly discovered threat, we also provide discussions on potential countermeasures, limitations, and future works of this new threat.
 - [Code](https://anonymous.4open.science/r/Tuner_code/readme.md)

### Tuner Audio Samples

|Tuner Duration|Speech Sample|
|--------------|-------------|
|1.5s|<audio src="samples/tuner-language/tuner-1.5.wav" type="audio/wav" controls preload></audio>|
|2.0s|<audio src="samples/tuner-language/tuner-2.wav" type="audio/wav" controls preload></audio>|
|3.5s|<audio src="samples/tuner-language/tuner-3.5.wav" type="audio/wav" controls preload></audio>|

