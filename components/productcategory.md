# productcategory

## Standard implementation

{% hint style="info" %}
The _**Product Category**_ is a brief of the available products, categorized.
{% endhint %}

![Product category component](https://github.com/miriamcastellon/st-design/tree/10a3297df124277b17d6268d0c90d09255da081f/design-system/.gitbook/assets/productcategory.png)

### Categories and products

!&gt; The order matters. They need to appear in the same order as followed.

We will show the cheapest price, with the maximum of pax shown, and **we will never repeat the same** _**subcategory**_ **vehicle**.

* Standard
  * **Private taxi** \(1-6 pax\): tx1, tx2, tx3, lmtx3, lmtx4, tx4, citytx3, citytx4, citytx5, citytxb4, citytxbig6, citytx6
  * **Private Minivan** \(1-8 pax\): lmmv5, mv5, lmmv6, lmmv7, mv7, lmmv8, mv8
  * **Shuttle** \(no min., no max.\): expsh, expsh5, sh10, sh
  * **WAV** \(1-6 pax\): wav2, wav4, wav5, wav6
* Premium
  * **Premium taxi** \(1-4 pax\): premtx3, premtx4
  * **Premium Minivan** \(1-8 pax\): premmv5, premmv6, premmv7, premmv8
  * **VIP taxi** \(1-4 pax\): viptx3, viptx4
* Large capacity
  * **Minibus** \(1-12 pax\): mb9, mb10, mb11, mb12
  * **Private Minicoach** \(1-35\): mch13, mch14, mch15, mch16, mch17, mch18, mch19, mch20, … mch35
  * **Private Coach** \(1-71 pax\): ch36… ch71
  * **Premium Minibus** \(1-18 pax\): premmb9, premmb10, premmb11, premmb12, premmb15, premmb16, premmb18 
  * **Premium Minicoach** \(1-31 pax\): premmch16, premmch20, premmch22, premmch31

### Mobile

The basic implementation for small screens includes a horizontal scrolling if it has more than one element in the list. The category tab will highlight the clicked category.

### Tablet

### Desktop

