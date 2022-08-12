terraform(-conda) mirror
===================

Mirror of terraform for pre-commit with conda as a language.

* For pre-commit: see https://github.com/pre-commit/pre-commit
* For terraform: see https://github.com/terraform/terraform

### Using terraform with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/Quantco/pre-commit-mirrors-terraform
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: terraform-conda
```
