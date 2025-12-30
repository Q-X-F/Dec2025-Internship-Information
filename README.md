# Dec2025-Internship-Information
About my 2-week internship in December 2025

From 2025-12-15 to 2025-12-26, I was an intern at Yangtze Delta Industrial Innovation Center of Quantum Science and Technology (Chinese name 量子科技长三角产业创新中心), located in Suzhou, China. I have signed an NDA, which I read carefully, and the information I share here complies with it. This repo contains my Certificate of Completion in both English and Chinese. Below is a summary of my internship.

I worked in Systems Theory Department (体系理论总体部), and was initially assigned to rewrite a Python implementation of an algorithm in C++. This involved learning on-the-go the C++ equivalents of built-in Python data structures. One additional challenge I encountered was that the tests were also written in Python, meaning I either had to rewrite the tests too, or find a way to have the Python test call my C++ functions. Since the former relied further on the correctness of my translation of the test, I chose the latter option by utilising the pybind11 library.

As I completed the translation task sooner than expected, I brainstormed with my supervisor some modifications that could improve the running time and output quality of the algorithm, one of which used multithreading. I implemented these modifications directly in C++, using preprocessor directives to quickly switch between versions for testing and results comparison. During this process, I added test cases in Python that are more appropriate for the application of the algorithm and provided further assurance of my implementation's correctness.

At the end of my internship, I finalised two versions of the algorithm with time-vs-output-quality tradeoffs against each other, but both improving on the original version. I ensured the source code is cleaned up and extensively commented. Additionally, I submitted a report that included simplified explanations of both algorithms in pseudocode, as well as data collected from tests arranged in tabular form.
