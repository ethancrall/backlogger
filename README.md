# BackLogger
BackLogger is a multi-artifact repository mining framework that extracts and analyzes technical debt signals from software repositories, including: 

* **Code smells** identified through static analysis
* **Refactoring commits** detected via commit message patterns and code diff analysis 
* **`TODO` / `FIXME`** annotations categorized by urgency and complexity
* **Architectural decay signals** derived from structural metrics

We strengthen this mining pipeline with a large language model (LLM) component that performs semantic classification of debt into four canonical categories: 

1. Design debt
2. Documentation debt
3. Test debt
4. Code debt

The LLM component will also assess the urgency of repayment and identify contextual debt accumulation triggers, such as deadline pressure and changes in team composition. We believe that LLM-assisted semantic analysis will offer software teams a much better foundation for informed debt management decisions.

**Note:** This research project was created by **Ethan Crall, Kale Dodson, Thomas Latawiec, and Jackson Weil** as part of their **COSC 540: Advanced Software Engineering** class at the **University of Tennessee, Knoxville**.
