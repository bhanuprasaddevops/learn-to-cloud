#चरण 4: DevOps को आधारभूत कुराहरू

लेखक: [GPS](https://twitter.com/madebygps)

## यो चरण क्लाउडमा कसरी लागू हुन्छ?

DevOps भनेको तपाईको समाधानहरू डिप्लोयमेन्टदेखि अपडेटहरू सम्म कुशलतापूर्वक चलाउनको लागि हो।
यो क्लाउडको लागि विशिष्ट छैन, किनकि तपाईंले DevOps अभ्यासहरू अन-प्रेम र हाइब्रिड वातावरणमा पनि लागू गर्न सक्नुहुन्छ। DevOps एकल भूमिकामा सीमित छैन। यद्यपि अधिकांश कम्पनीहरूले DevOps मा भूमिकाहरू समर्पित गरेका छन्। यदि तपाइँको उद्देश्य एक DevOps ईन्जिनियर बन्ने हो भने, यो चरणले तपाइँलाई सुरु गराउनेछ तर तपाइँ गहिरो जानु पर्छ।
DevOps एक संस्कृति हो, र कुनै विशेष उपकरण वा सेवा होइन। DevOps के हो भनेर पढ्नुहोस्। प्रत्येक क्लाउड प्लेटफर्ममा DevOps उपकरणहरूको सूट हुन्छ, मैले यहाँ केही लेखहरू लिङ्क गरेको छु।

- [Microsoft - DevOps के हो](https://azure.microsoft.com/overview/what-is-devops/#overview)
- [AWS - DevOps के हो](https://aws.amazon.com/devops/what-is-devops/)
- [IBM - एक DevOps पूर्ण गाइड](https://www.ibm.com/cloud/learn/devops-a-complete-guide)

मलाई पनि यो पढ्न लायक लाग्छ [The Phoenix Project](https://itrevolution.com/the-phoenix-project/) यो पढ्नको लागि धेरै रमाइलो छ किनभने यो एक काल्पनिक कथा हो तर यसले DevOps को महत्व बताउँछ। तर यदि तपाइँ समान विचारहरूको साथ पाठ्यपुस्तक जस्तै केहि मनपर्छ भने,जाँच गर्नुहोस् [The DevOps Handbook](https://itrevolution.com/the-devops-handbook/).

तपाईंले पूरा गर्नुपर्थ्यो [Cloud Resume Challenge](https://cloudresumechallenge.dev/) अघिल्लो चरणमा। त्यो परियोजनाले तपाईंलाई DevOps अवधारणाहरूसँग परिचय गराउँछ, यदि तपाईंसँग छैन भने, फिर्ता जानुहोस् र त्यसो गर्नुहोस्। 

## How to break down this phase

| अर्डर | विषय                | समय प्रतिबद्धता |
|-------|-----------------------|-------------------|
| १ | CI/CD GitHub कार्यहरूको साथ | 1 हप्ता
| २ | Terraform संग IaC | 1 हप्ता        |
| 3 | डकरको साथ कन्टेनरहरू | 1 हप्ता          |
| 4 | Kubernetes संग कन्टेनर अर्केस्ट्रेशन | 1 हप्ता          |
| 5 | Prometheus संग निगरानी | 1 हप्ता     |

निस्सन्देह तपाईले चाहानु भएको धेरै समय खर्च गर्न स्वतन्त्र महसुस गर्नुहोस्, मानिसहरूले टाइमलाइन र ब्रेकडाउनको लागि सोधेका छन् त्यसैले मैले यसलाई थपेको छु। प्रत्येक DevOps अभ्यास मामिला, तर यी एक प्रविष्टि/जुनियर स्तर मा सबै भन्दा बढी प्रयोग गरिन्छ। तपाइँ पहिले नै चरण 2 बाट संस्करण नियन्त्रण संग परिचित हुनुपर्छ।
## स्रोतहरू

| स्रोतहरू                                                      | नोटहरु                                                                                       |
| :------------------------------------------------------------------ | :----------------------------------------------------------------------------------------- |
| [GitHub कार्यहरू ट्यूटोरियल - आधारभूत अवधारणाहरू र डकरसँग CI/CD पाइपलाइन](https://www.youtube.com/watch?v=R8_veQiYBjI)|नाना DevOps को रानी हुन् र त्यहाँ केहि उत्कृष्ट DevOps सिकाउने सामग्री सिर्जना गर्छन्। यो ट्यूटोरियलले तपाईंलाई GitHub कार्यहरूमा परिचय गराउनेछ।
| [Terraform कोर्स पूरा गर्नुहोस् - BEGINNER देखि PRO सम्म!](https://www.youtube.com/watch?v=7xngnjfIlK4)| तपाइँको AWS पूर्वाधार स्वचालित गर्न Terraform कसरी प्रयोग गर्ने जान्नुहोस्।
| [शुरुआतीहरूको लागि डकर ट्यूटोरियल](https://youtu.be/3c-iBn73dDE) | धेरै डेमोहरू र पछाडिका अवधारणाहरू व्याख्या गर्दै डकर ह्यान्ड्स-अन कोर्स पूरा गर्नुहोस्, ताकि तपाईंले यसलाई वास्तवमै बुझ्नुहुन्छ।
| [निरपेक्ष शुरुआतीहरूको लागि Kubernetes क्र्यास कोर्स](https://youtu.be/s_o8dwzRlu4) | ह्यान्ड्स-अन Kubernetes ट्यूटोरियल | 1 घण्टामा Kubernetes सिक्नुहोस् - शुरुआतीहरूको लागि Kubernetes पाठ्यक्रम
| [प्रोमेथियस निगरानी ट्यूटोरियल पूरा गर्नुहोस्](https://youtube.com/playlist?list=PLy7NrYWoggjxCF3av5JKwyG7FFF9eLeL4) | प्रोमेथियस निगरानी ट्यूटोरियल पूरा गर्नुहोस्

## परियोजनाहरू

| शीर्षक                                                       | स्रोत                                                                        |
| :----------------------------------------------------------- | --------------------------------------------------------------------------------- |
| [Azure DevOps प्रयोग गरेर DevOps यात्रा](https://github.com/thomast1906/DevOps-Journey-Using-Azure-DevOps) | यो ट्यूटोरियल/ल्याब सेटअपले तपाईंलाई Azure DevOps प्रयोग गरेर DevOps यात्रामा लैजान्छ। तपाइँको पाइपलाइन सेटअप देखि तपाइँको Azure Kubernetes क्लस्टर मा एक आवेदन तैनाती सम्म! |
| [DevOps द हार्डवे - Azure](https://github.com/thomast1906/DevOps-The-Hard-Way-Azure) | यो ट्यूटोरियलले Azure मा अनुप्रयोगहरू र क्लाउड सेवाहरू/क्लाउड पूर्वाधारहरू प्रयोग गर्न DevOps प्रविधिहरू र अभ्यासहरू प्रयोग गर्ने वातावरण सेटअप गर्नको लागि पूर्ण, वास्तविक-विश्व समाधान समावेश गर्दछ। |
| [DevOps द हार्डवे - AWS](https://github.com/AdminTurnedDevOps/DevOps-The-Hard-Way-AWS) | यस ट्यूटोरियलले AWS मा एपहरू र क्लाउड सेवाहरू/क्लाउड पूर्वाधारहरू प्रयोग गर्नका लागि DevOps प्रविधिहरू र अभ्यासहरू प्रयोग गर्ने वातावरण सेटअप गर्नको लागि पूर्ण, वास्तविक-विश्व समाधान समावेश गर्दछ। |

## यस चरणको अन्त्यमा तपाईले परिचित हुनै पर्ने कुराहरू

- प्रत्येक DevOps अभ्यास व्याख्या गर्न सक्षम हुनुहोस्
  - किन प्रत्येकले महत्त्वपूर्ण छ।
  - प्रत्येकले के पूरा गर्छ।
  - प्रत्येक अभ्यास लागि सबैभन्दा लोकप्रिय उपकरण।

- तपाईंको GitHub मा व्यक्तिगत परियोजनाहरू छन्। तपाईंको कम्तिमा २ परियोजनाहरूको लागि:
  - एक CI/CD पाइपलाइन छ।
  - प्रत्येक परियोजनाको लागि IaC फाइलहरू छन्।
  - प्रत्येकको लागि अनुगमन लागू गर्नुहोस्।
    - निश्चित गर्नुहोस् कि तपाइँ लगिङ र मेट्रिक्स डेटा बुझ्न सक्नुहुन्छ।
  - यदि तपाइँको परियोजनाको साथ केहि गलत भएको थियो भने, कसरी समस्या निवारण गर्ने भनेर बुझ्नुहोस्।

## तपाईंले हेर्न चाहनुहुने प्रमाणपत्रहरू
- [AWS प्रमाणित DevOps इन्जिनियर - व्यावसायिक](https://aws.amazon.com/certification/certified-devops-engineer-professional/?ch=sec&sec=rmg&d=1)
- [माइक्रोसफ्ट प्रमाणित: DevOps ईन्जिनियर विशेषज्ञ](https://docs.microsoft.com/en-us/learn/certifications/devops-engineer/)


## अब के

[चरण 5 मा जानुहोस्: क्लाउड सुरक्षा आधारभूतहरू](../phase5/README.md)
