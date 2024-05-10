# **A Watermark for Large Language Models**
**Authors: John Kirchenbauer, Jonas Geiping, Yuxin Wen, Jonathan Katz, Ian Miers, Tom Goldstein (University of Maryland)**

## **Description:**
As AI-generated content becomes more pervasive, distinguishing between human and machine-generated text is critical to prevent misuse. In this blog, we introduce a novel approach detailed in a recent research paper where watermarks are embedded into the output of large language models (LLMs) like GPT. These watermarks are undetectable to humans but can be algorithmically identified, even from short text snippets.

We'll explore how this watermarking technology works, employing a technique that subtly alters the probability of certain words (green list) while avoiding others (red list). This allows the detection of AI-generated text without access to the model's internal configurations or external databases.

The blog will cover the practical implications of this technology, such as its use by social media platforms to identify synthetic content, and its minimal impact on text quality. We will also delve into the robustness of this method against various attempts to remove the watermark.

Join us as we discuss the potential of watermarking to provide a layer of security and authenticity in a world increasingly dominated by AI-generated content.

<p align="right">
    <img src="watermark.png" alt="Watermarking Image" width="400"/>
</p>

## **Motivation**

1. **Harm Reduction:** The paper highlights the potential harms of large language models, such as their use in social engineering, election manipulation, and creating fake content. It proposes a watermarking system to mitigate these risks by making synthetic text detectable.
2. **Invisible Yet Detectable:** The proposed watermark is designed to be invisible to humans but detectable algorithmically from a short span of tokens, which ensures that it does not affect the readability or the utility of the text.
3. **Operational Efficiency:** The watermarking method can be implemented with minimal impact on the language model’s performance and without requiring access to the model's internal parameters or API, making it efficient and broadly applicable【14:1†source】.


## **Research Objective**



### **Methodology**

# 1) Hard


# 2) Soft 


## **Experiments and Results**

### **Dataset**

## Results

## **Conclusion**


---

*Code and dataset can be found on the [GitHub](https://github.com/jwkirchenbauer/lm-watermarking).*
