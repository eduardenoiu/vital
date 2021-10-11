# VITAL
ViTAL is a tool which provides model-checking of EAST-ADL systems with regard to timing/behavioral requirements.
<img width="694" alt="Screen Shot 2021-10-11 at 10 35 28" src="https://user-images.githubusercontent.com/7644735/136759197-69213a35-7a27-4fe5-81df-3a9698d39444.png">

We implement an automatic model transformation so that UPPAAL PORT can handle EAST-ADL models as input and provide functional and timing behavior of functional blocks using timed automata semantics. UPPAAL PORT is an extension of UPPAAL tool which supports simulation and model-checking without conversion or flattening to the model of network of timed automata that is usually used in UPPAAL.

UPPAAL PORT uses a Partial Order Reduction Technique (PORT) in order to improve the efficiency of the model-checking analysis.

Download: https://www.dropbox.com/s/28caje6h1gevqp6/vitalFinal.zip?dl=0 

The latest version 0.32 is available for download, see also the release notes.

<img width="533" alt="Picture1" src="https://user-images.githubusercontent.com/7644735/136759478-b4e4d77b-5758-45f3-8f18-376147422901.png">

(1) Integrated EAST-ADL Platform Editor
(2) Timed Automata Editor
(3) UPPAAL PORT Simulator
(4) UPPAAL PORT Verifier

References:

Enoiu, E. P., Marinescu, R., Seceleanu, C., & Pettersson, P. (2012, July). Vital: A verification tool for east-adl models using uppaal port. In 2012 IEEE 17th International Conference on Engineering of Complex Computer Systems (pp. 328-337). IEEE. http://www.es.mdh.se.ep.bib.mdh.se/pdf_publications/2370.pdf 

Kang, Eun-Young, Eduard Paul Enoiu, Raluca Marinescu, Cristina Seceleanu, Pierre-Yves Schobbens, and Paul Pettersson. "A methodology for formal analysis and verification of EAST-ADL models." Reliability Engineering & System Safety 120 (2013): 127-138. http://www.es.mdh.se.ep.bib.mdh.se/pdf_publications/3881.pdf
