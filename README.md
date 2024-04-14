# Language-Imbalance-Can-Boost-Cross-lingual-Generalisation


Abstract
Multilinguality is crucial for extending recent advancements in language
modelling to diverse linguistic communities. To maintain high performance
while representing multiple languages, multilingual models ideally align
representations, allowing what is learned in one language to generalise
to others. Prior research has emphasised the importance of parallel data
and shared vocabulary elements as key factors for such alignment. In this
study, we investigate an unintuitive novel driver of cross-lingual generalisation: language imbalance. In controlled experiments on perfectly equivalent
cloned languages, we observe that the existence of a predominant language
during training boosts the performance of less frequent languages and
leads to stronger alignment of model representations across languages. Furthermore, we find that this trend is amplified with scale: with large enough
models or long enough training, we observe that bilingual training data
with a 90⁄10 language split yields better performance on both languages than
a balanced 50⁄50 split. Building on these insights, we design training schemes
that can improve performance in all cloned languages, even without altering the training data. As we extend our analysis to real languages, we find
that infrequent languages still benefit from frequent ones, yet whether language imbalance causes cross-lingual generalisation there is not conclusive.


अवश्य, यहाँ पेपर का सारांश हिंदी में दिया गया है:

**सारांश (Abstract):**
- **भाषा मॉडलों में बहुभाषिकता**: यह अध्ययन बहुभाषी मॉडलों की खोज करता है, जो आदर्श रूप से भाषाओं के बीच प्रतिनिधित्व को संरेखित करते हैं, और यह कैसे एक भाषा से दूसरी भाषाओं में सीखने को सामान्यीकृत कर सकते हैं।
- **भाषा असंतुलन के रूप में एक चालक**: यह एक अनूठा कारक, भाषा असंतुलन पेश करता है, जो दिखाता है कि प्रशिक्षण के दौरान एक प्रमुख भाषा कम आम भाषाओं के प्रदर्शन और संरेखण को बढ़ा सकती है।
- **पैमाने का प्रभाव**: बड़े मॉडलों या लंबे प्रशिक्षण के साथ, जहां 90/10 भाषा विभाजन एक संतुलित 50/50 विभाजन से बेहतर प्रदर्शन करता है।
- **प्रशिक्षण योजनाएं**: नई प्रशिक्षण योजनाएं प्रस्तावित की गई हैं जो सभी भाषाओं में प्रदर्शन को बिना प्रशिक्षण डेटा को बदले सुधार सकती हैं। हालांकि, वास्तविक भाषाओं पर भाषा असंतुलन का प्रभाव कम स्पष्ट है।

यह सारांश आपको पेपर की मुख्य अवधारणाओं का एक अवलोकन प्रदान करता है।
