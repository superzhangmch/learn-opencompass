- math_prm800k_500_0shot_cot_academic_gen.py 
- math_prm800k_500_0shot_cot_gen.py 
- math_prm800k_500_gen.py
- math_prm800k_500_0shot_nocot_gen_b27274.py
- math_prm800k_500_0shot_nocot_genericllmeval_gen_63a000.py 
- math_prm800k_500_0shot_nocot_genericllmeval_xml_gen_63a000.py 
- math_prm800k_500_0shot_nocot_llmjudge_gen_63a000.py 

1. 以上都是 0-shot
2. 评估：
   - GenericLLMEvaluator：math_prm800k_500_0shot_nocot_genericllmeval_gen_63a000.py  math_prm800k_500_0shot_nocot_genericllmeval_xml_gen_63a000.py
   - LMEvaluator： math_prm800k_500_0shot_nocot_llmjudge_gen_63a000.py
   - 其他用：MATHEvaluator
3. step by step:
   - math_prm800k_500_gen.py
   - math_prm800k_500_0shot_cot_gen.py
