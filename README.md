# Currency Apps
(Introduction)
Aplikasi sederhana untuk windows

## Scope of functionalities
- Mengkonversi nilai mata uang USD ke RP
- Filter kesalahan input

## How Does It WORKS ?
    public string usdToIdr(string nominal)
    {
        var nominalDouble = Convert.ToDouble(nominal);
        var result = nominalDouble * 15000;
        return Convert.ToString(result);
    }
