# GP / GC review

Monthly galvanised plain coil (GP) and galvanised corrugated sheet (GC)
review for Evonith Value Steel:
tonnage and product mix from the invoice data, receivables and collections
from the daily debtors files.

The page is a static snapshot. It carries its own data, so `index.html` is the
whole site. Regenerate it with the pipeline in the `dashboard scripts` folder
of the working copy:

    python refresh.py --from "<folder of saved outstanding files>"
    python export_web.py
    python build_web.py
    python publish.py
