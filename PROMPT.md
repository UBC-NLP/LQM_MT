# LQM Translation Prompt

This file mirrors the released translation prompt used in the repository materials.

```python
def create_prompt(src, trg):
    if src == 'ENG':
        prompt = f'Translate the following English phrase into {langs_map[trg]} Arabic dialect written in Arabic script. Your response must only contain the translated text, with no additional explanations or labels.'
    else:
        prompt = f'Translate the following {langs_map[src]} Arabic dialect phrase into English. Your response must only contain the translated text, with no additional explanations or labels.'
    return prompt
```

Original source file: [LQM_translation_prompt_extracted.docx](LQM_translation_prompt_extracted.docx)
