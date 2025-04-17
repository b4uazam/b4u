
### **Fundamental Review of the Trading Book (FRTB) – Simplified Explanation**
**What is FRTB?**  
FRTB is a set of global banking rules (by Basel Committee) to make banks like J.P. Morgan calculate trading risks more accurately. It forces banks to:  
1. **Separate trading vs. banking activities** – What’s actively traded (stocks, bonds, derivatives) vs. held long-term.  
2. **Use stricter risk models** – Banks must either:  
   - **Standardized Approach (SA):** Follow fixed rules for risk calculations.  
   - **Internal Models Approach (IMA):** Use their own models (but with tougher requirements).  

**Key Goal:** Prevent banks from underestimating risks (like in the 2008 crisis).  

---

### **How FRTB Affects Interest Rate (IR) & Foreign Exchange (FX) Risk Calculations**  
Under FRTB, banks must compute risk metrics like:  
- **Expected Shortfall (ES):** "How bad can losses get in a crisis?" (replaces VaR).  
- **Sensitivities-Based Method (for SA):** Measure how much prices move due to rate/FX changes.  

#### **1. Interest Rate (IR) Risk Example**  
- **Problem:** If interest rates rise, bond prices fall. How much could J.P. Morgan lose?  
- **FRTB Calculation:**  
  - Break down risks into "buckets" (e.g., short-term vs. long-term rates).  
  - Use regulatory formulas to aggregate risks across currencies/maturities.  

#### **2. Foreign Exchange (FX) Risk Example**  
- **Problem:** If EUR/USD drops, how much does J.P. Morgan lose on EUR holdings?  
- **FRTB Calculation:**  
  - Compute FX sensitivities (how much portfolio value changes per 1% FX move).  
  - Apply regulatory correlations to net offsets (e.g., EUR gains vs. JPY losses).  

---

### **How Functors Help (Tech-Simplified)**  
**Functors = Math tools to automate risk calculations.**  
- Think of them as pre-built Excel formulas but for complex risk math.  
- **How J.P. Morgan Might Use Functors:**  
  1. **Inputs:** Market data (rates, FX prices) + portfolio positions.  
  2. **Apply Functors:**  
     - **IR Functor:** Computes bond price changes when rates shift.  
     - **FX Functor:** Calculates portfolio loss if USD strengthens by 1%.  
  3. **Output:** Risk numbers fed into reports/regulatory filings.  

**Why Functors?**  
- Speed up thousands of repetitive calculations.  
- Ensure consistency (avoids human errors in manual math).  

---

### **Layman’s Summary**  
- **FRTB** = Rules to make banks like J.P. Morgan measure trading risks more carefully.  
- **IR/FX Calculations** = "If interest rates or currency rates move, how much do we lose?"  
- **Functors** = Software tools that crunch these numbers fast and accurately.  

Would you like a specific example (e.g., a bond or currency trade)?
