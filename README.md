# PyCCE-RC

**PyCCE-RC** is a Python package for estimating panel data models using the **Common Correlated Effects (CCE)** methodology. It extends the original CCE framework by incorporating a recently proposed **Rank Condition (RC) test** and a **cross-sectional augmentation (CSA)** algorithm to address potential rank failures, enabling consistent estimation in a wider range of settings.

## 📦 Features

- Implementation of all three CCE estimators:
  - **Individual-specific CCE**
  - **Mean Group CCE**
  - **Pooled CCE**

- Built-in tools for:
  - Verifying the **rank condition** (RC test)
  - Performing **CSA augmentation** to (potentiall) restore the RC

- Compatible with balanced and unbalanced panel data

- Modular design:
  - `py_cce.base`: core data structures and estimation logic
  - `py_cce.models`: individual estimator classes
  - `py_cce.utils`: CSA computation, rank condition testing, and other utilities

- Fully type-checked and linted
- Includes documentation

## 🛠 Installation

```bash
pip install pycce-rc
```

## License

This project is licensed under the GNU General Public License v3.0 or later (GPL-3.0-or-later).
See the [LICENSE](./LICENSE) file for details.
