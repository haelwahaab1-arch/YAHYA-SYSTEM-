http://INTEGRATION.md
> كيف تضع الكلمة في موضعها تقنياً

المسار
Input -> Gemini (توليد) -> YAHYA (حوكمة) -> Output

ماذا تفحص YAHYA؟
هل فيه ظلم؟
هل يخالف القانون؟
هل الحق في موضعه؟

إن كان سليماً: يمر.
إن لم يكن: يصحح.

مثال (Python)
def yahya_govern(text: str) -> str:
    if has_zulm(text):
        text = remove_zulm(text)
    if violates_law(text):
        text = correctbylaw(text)
    text = place_right(text)
    return text

raw = http://gemini.generate(prompt)
governed = yahya_govern(raw)

القاعدة
لا نعظم إلا الله.
وما دون ذلك التزام بالكلمة.
