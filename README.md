# Musical-Style-Transfer-with-GANs

Advances in the field of machine learning have led to the introduction of generative adversarial networks, or GANs, with image style transfer being a novel application. Recently, the same concept of style transfer has been explored in the domain of music, through genre conversion. For example, a piece from the classical period could be converted to a modern pop style. A successful transfer between genres is one that maintains content, such as chords and general structure, of the original piece, while changing stylistic elements to align with the target genre. This project presents a novel method to achieve this by using chroma features. A chromagram is a visual representation of music that only records note density, thus extracting only the most important elements of a piece. By using the chromagram as a medium, the realism and efficacy of the transfer between genres can be improved. To explore this, three genres were used in testing: pop, classical, and jazz. To evaluate the success of the transfer, two metrics were used: the Tonnetz distance, and a separate genre classifier. Tonnetz distance is a formula prevalent in music theory that measures harmonic distance. The second metric is a separate genre classifier, which is a CNN that tries to classify the transfers into genre categories based on pre-trained data. The efficacy of the transfer is evidenced by the classifier’s high success rate, as well as the low Tonnetz distance, signifying the maintenance of harmonic structure. This novel approach to genre transfer holds potential for future applications of GANs.
