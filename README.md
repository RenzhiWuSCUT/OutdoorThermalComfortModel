# OutdoorThermalIndex

The code for commonly used outdoor thermal comfort models.
常用室外热舒适模型的代码。

Here, we have collected the code for commonly used outdoor thermal comfort models, which include PET, SET*, UTCI, WBGToutdoor, COMFA, and COMFAcourtyard.
在这里，我们整理了一些常用的室外热舒适模型的代码，包括PET、SET*、UTCI、WBGToutdoor、COMFA和COMFAcourtyard。

If you use this code in academic research, we recommend citing the following article: R. Wu, X. Fang, R. Brown, S. Liu, H. Zhao, "The COMFAcourtyard Model for Assessing Courtyard Thermal Comfort in Hot and Humid Regions: A Comparative Study with Existing Models," Build. Environ. This article provides a detailed description of the PET, SET*, COMFA, and COMFAcourtyard algorithms. Additionally, when using specific outdoor thermal comfort models, please also cite the corresponding references.
如果您在学术论文中使用本代码，我们建议您引用以下文章：R. Wu, X. Fang, R. Brown, S. Liu, H. Zhao, "The COMFAcourtyard Model for Assessing Courtyard Thermal Comfort in Hot and Humid Regions: A Comparative Study with Existing Models," Build. Environ. 该论文详细介绍了PET、SET*、COMFA和COMFAcourtyard算法的相关内容。同时，当您使用具体的室外热舒适模型时，也请引用各模型对应的参考文献。

Reference of WBGToutdoor:
[1] K. Blazejczyk, J. Baranowski, A. Blazejczyk, Heat stress and occupational health and safety - Spatial and temporal differentiation, Misc. Geogr. 18 (2014) 61–67. https://doi.org/10.2478/mgrsd-2014-0011.
[2] Chriswmackey, ladybug-legacy, (2018). https://github.com/ladybug-tools/ladybug-legacy.
    
Reference of UTCI:
[1] D. Fiala, Dynamic Simulation of Human Heat Transfer and Thermal Comfort, Sustain. Dev. 45 (1998) 1. https://www.dora.dmu.ac.uk/xmlui/handle/2086/4129.
[2] D. Fiala, K.J. Lomas, M. Stohrer, A computer model of human thermoregulation for a wide range of environmental conditions: The passive system, J. Appl. Physiol. 87 (1999) 1957–1972. https://doi.org/10.1152/jappl.1999.87.5.1957.
[3] D. Fiala, G. Havenith, P. Bröde, B. Kampmann, G. Jendritzky, UTCI-Fiala multi-node model of human heat transfer and temperature regulation, Int. J. Biometeorol. 56 (2012) 429–441. https://doi.org/10.1007/s00484-011-0424-7.
[4] ISB Commission 6, C.A. 730, UTCI Universal Thermal Climate Index Documents, (n.d.). http://www.utci.org/utci_doku.php.
[5] B. P, F. D, B. K, H. I, J. G, K. B, T. B, H. G, Deriving the operational procedure for the Universal Thermal Climate Index (UTCI)., Int. J. Biometeorol. 56 (2012) 481–494. https://pubmed.ncbi.nlm.nih.gov/21626294/.
[6] Chriswmackey, ladybug-legacy, (2018). https://github.com/ladybug-tools/ladybug-legacy.

Reference of SET*:
[1] J.A.. Stolwijk, A Mathematical Model of Physiological Temperature Regulation in Man, NASA Contract. Reports. 303 (1971) 14–30.
[2] GAGGE AP, STOLWIJK JAJ, NISHI Y, Effective temperature scale based on a simple model of human physiological regulatory response, ASHRAE Trans. 77 (1971) 247–263.
[3] A.P. Gagge, A.P. Fobelets, L.G. Berglund, Standard Predictive Index of Human Response To the Thermal Environment., ASHRAE Trans. 92 (1986) 709–731.
[4] C. Fountain, Marc;Huizenga, A Thermal Sensation Model For Use By The Engineering Profession, (1995). https://escholarship.org/uc/item/89d5c8k7.
[5] Building simulation resources: SET_star, (2002). http://news-sv.aij.or.jp/kankyo/s12/Resource/ap/SET_star/SET_star.htm.

Reference of PET:
[1] P. Höppe, Die Energiebilanz des Menschen, Wiss Mitt Meteorol Inst Univ München. 49 (1984) 173.
[2] Hoppe PR, Heat balance modelling, Experientia. 49 (1993) 741–746.
[3] VDI, Umweltmeteorologie - Methoden zur human-biometeorologischen Bewertung von Klima und Lufthygiene für die Stadt- und Regionalplanung - Teil I: Klima - VDI 3787, (2008) 1–32.
[4] Chinese University of Hong Kong department of Architecture, Urban Climatic Map and Standards for Wind Environment - Feasibility Study Technical Input Report No . 1 : Methodologies and Findings of User ’ s Wind Comfort Level Survey Nov 2008, (2008) 151. http://www.pland.gov.hk/pland_en/p_study/prog_s/ucmapweb/ucmap_project/content/reports/Comfort_Level_Survey.pdf.
[5] E. Walther, Q. Goestchel, The P.E.T. comfort index: Questioning the model, Build. Environ. 137 (2018) 1–10. https://doi.org/10.1016/j.buildenv.2018.03.054.   @staticmethod
[6] Chriswmackey, ladybug-legacy, (2018). https://github.com/ladybug-tools/ladybug-legacy.

Reference of COMFA:
[1] W. Cheng, R.D. Brown, An energy budget model for estimating the thermal comfort of children, Int. J. Biometeorol. 64 (2020) 1355–1366. https://doi.org/10.1007/s00484-020-01916-x.
[2] N.A. Kenny, J.S. Warland, R.D. Brown, T.G. Gillespie, Part A: Assessing the performance of the comfa outdoor thermal comfort model on subjects performing physical activity, Int. J. Biometeorol. 53 (2009) 415–428. https://doi.org/10.1007/s00484-009-0226-3.
[3] N.A. Kenny, J.S. Warland, R.D. Brown, T.G. Gillespie, Part B: Revisions to the COMFA outdoor thermal comfort model for application to subjects performing physical activity, Int. J. Biometeorol. 53 (2009) 429–441. https://doi.org/10.1007/s00484-009-0227-2.
[4] J.K. Vanos, J.S. Warland, T.J. Gillespie, N.A. Kenny, Improved predictive ability of climate-human-behaviour interactions with modifications to the COMFA outdoor energy budget model, Int. J. Biometeorol. 56 (2012) 1065–1074. https://doi.org/10.1007/s00484-012-0522-1.
[5] R.D. Brown, T.J. Gillespie, Estimating outdoor thermal comfort using a cylindrical radiation thermometer and an energy budget model, Int. J. Biometeorol. 30 (1986) 43–52. https://doi.org/10.1007/BF02192058.

Reference of COMFAcourtyard:
[1] R. Wu, X. Fang, R. Brown, S. Liu, H. Zhao, The COMFAcourtyard Model for Assessing Courtyard Thermal Comfort in Hot and Humid Regions: A Comparative Study with Existing Models, Build. Environ.
[2] W. Cheng, R.D. Brown, An energy budget model for estimating the thermal comfort of children, Int. J. Biometeorol. 64 (2020) 1355–1366. https://doi.org/10.1007/s00484-020-01916-x.
[3] N.A. Kenny, J.S. Warland, R.D. Brown, T.G. Gillespie, Part A: Assessing the performance of the comfa outdoor thermal comfort model on subjects performing physical activity, Int. J. Biometeorol. 53 (2009) 415–428. https://doi.org/10.1007/s00484-009-0226-3.
[4] N.A. Kenny, J.S. Warland, R.D. Brown, T.G. Gillespie, Part B: Revisions to the COMFA outdoor thermal comfort model for application to subjects performing physical activity, Int. J. Biometeorol. 53 (2009) 429–441. https://doi.org/10.1007/s00484-009-0227-2.
[5] J.K. Vanos, J.S. Warland, T.J. Gillespie, N.A. Kenny, Improved predictive ability of climate-human-behaviour interactions with modifications to the COMFA outdoor energy budget model, Int. J. Biometeorol. 56 (2012) 1065–1074. https://doi.org/10.1007/s00484-012-0522-1.
[6] R.D. Brown, T.J. Gillespie, Estimating outdoor thermal comfort using a cylindrical radiation thermometer and an energy budget model, Int. J. Biometeorol. 30 (1986) 43–52. https://doi.org/10.1007/BF02192058.
    