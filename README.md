# FEC_OSL
Encrypted traffic classification is crucial for enhancing network management, service quality, and security. In realworld scenarios, emerging traffic flows often include unknown
classes, posing significant challenges in identifying unknown flows
while simultaneously classifying known ones. Existing deep learning methods typically rely on the closed-world assumption, which
limits their performance in handling unknown traffic in openworld scenarios. To address these limitations, we propose an endto-end fine-grained encrypted traffic classification method based
on open-set semi-supervised learning, called FEC-OSL. This
method comprises three mutually reinforcing core components.
First, we design a dual-branch flow feature extraction module
to capture detailed and discriminative flow features. Second, we
introduce a novel energy-based perspective that leverages energy
boundary learning to distinguish known flows from unknown
flows, enabling precise detection of known classes. Finally, an
adaptive deep clustering approach integrates feature learning
with clustering to achieve fine-grained classification of unknown
flows. We conduct extensive experiments on three real-world
datasets, and the results validated that our proposed method
exhibits outstanding performance in handling both known and
unknown encrypted traffic in open-world scenarios.
