+++
title = "Aranya"
date = 2025-10-10
+++

Aranya is a proof-of-concept of an education platform that aims to reward teachers and learners by connecting course metrics to upgradeable credentials on the Flare blockchain. Credentials get minted as seeds and grow whenever milestones are reached, ultimately becoming a mature tree (of wisdom!). For teachers these milestones represent the amount of students enrolled in their course, for learners these milestones represent the amount of modules completed they completed in a course.

{{ resize_image(path="/public/images/slide.jpeg", width=800, height=400) }}
Minting the credentials on the Flare blockchain has two purposes. First, in an era where any document can easily be forged with assistance of AI, the transparency and verifiability of blockchain data guarantees the legitimacy of credentials.

Second, using the Flare Data Connector (FDC) allows verification and usage of data from any JSON web API inside smart contracts. This creates a cool opportunity to have the teacher/student credentials on the blockchain to directly upgrade by verifying the course progress data from Aranya's own API.

I built this project as part of an 8 week Flare incubator program during the summer of 2025. It was a fun opportunity to experiment with the Flare technology and integrating Web2 data into Web3 smart contracts. I think there are definitely more use cases for this in the future, but currently the process of submitting attestations and generating proof takes too long (a couple of minutes per transaction) to be practically usable in most use cases. I'm looking forward to see how the technology develops and possibly I'll revisit this project in the future.