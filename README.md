# Broadlink IR Codes Conversor To UFO MQTT UFO-R11 Codes
Home assistant Broadlink IR Codes Conversor To MQTT MOES UFO-R11 Codes

if you are using smartir climate addon in home assistant, with this conversor you can convert the files with broadlink codes to UFO-R11 Codes

using :

python3 python.exe btu.py 1740.json > 1740converted.json

remember for UFO-R11, your final json file must include in every command that sintax, (code it's every code)

off": "{\"ir_code_to_send\": \"code\"}",


Example

"off": "{\"ir_code_to_send\": \"CEcNegaSAAC0ADgAsAkmAHBZIB0gHmBIADQCfAC0\"}",

File example.

<sup> 
  
{    
 
    "manufacturer": "Mitsubishi Electric",    
    "supportedModels": [
        "MSY-GM18VA"
    ],
    
    "supportedController": "MQTT",  
    "commandsEncoding": "Raw",
    "minTemperature": 16.0,
    "maxTemperature": 31.0,
    "precision": 1.0,
    "operationModes": [
        "cool"
    ],
    "fanModes": [
        "low"
    ],
    "commands": {
        "off": "{\"ir_code_to_send\": \"CEcNegaSAeYE0mADAJJgAQXSAV8B0gFAE0AHQA9AC0ADgAsAkmAHBZIB0gHmBIADQCfAC0AXAJIgAUAPAZIBgANAC0AjwA8AkmABQAfgAQPgCx/gHxPgA0dAawfmBJIBkgHSAeADPwHmBIADQBcAkmABQAfgAQPgAx/AN8ATQAcAkmABAdIBgAuAB8ALAJJgAUAHQANAAeADB+AHC0APQANAAUAH4AEDwHeAE0ABAdIB4B8TQCsAkmAB4AMH4AEL4AtHgB9ABwGSAYAFQAHACeADBwHSAYDrQAEB0gFAA0APQANACwFSLEJHAdIBQA8I5gSSAZIB0gGSYAEB0gHAD0B/AeYEgAOAF0AHQAEE0gHmBJIgAwjSAZIB0gHmBJIgAwPSAZIBgAPgAQsFkgHmBJIB4AcBAtIBkuAAAeABC+AfCeABAeABMQGSAUALQGtAA0ALwANAAUATQANAAeADFwHSAUDhAZIBQBsB5gSAC0APQAMB5gRAAwBfIAcDXwHSAUADQA8FkgHSAV8BQAcD5gRfAUALgAMDkgHSAeALC+ArE8BL4AcHQEvAE0ALwAPgFxPAH8AHQDfgAwtAD0AD4BET4AXrgA8H5gRfARcCXwE=\"}",
        "cool": {
            "low": {
                "16": "{\"ir_code_to_send\": \"BykNjwbRAeoEgAMFRwHRAYoBgANAE+ADC8APwAdAG0ALQAPgBwvAD0AHQAPAI0AL4AkDQAEB0QHgA3sAimABQAfgEQPgBVNAAQHRAUADQBdAA0AL4AMDQBNAA+ADEwCKYAFABwHRAUAbQANAC8ADQA/AA+ADE0ALB+oENgLqBNEBQAvgDQMCigHRIAFABQCKoAGACUAFQAOAAeAHCUAPQAPAAeABC+AHCUAP4AMDQAHgAw9AC0ABQAfgDwNAAeADGwGKAUANAYoBQAXgAwMBigGA68ABQBuAAQXqBIoBkSxCRwGKAUALQANAHUADQAHgAQ8BRwFAC0ADA9EBigHAB8ALwA9ABwPqBEcBQBcF0QFHAeoEgAcF0QGKAeoEgAcB0QHAB+ADC+AnE0AvB0cBcgVHAdEBwEfACwOKAeoEgANACwHRAcAXA0cB6gRAA+AFE0AXAdEBQBMBigFAG0ADQAsB0QGAF0APA+oERwGAawVHATYCRwHAC0AHQANAF+ADA0AjQANAE0AH4AMD4C0TBAwBNgJHIANAB0AD4AMLQA9AA+AfE0Ar4AMDA98ANgLAD+ADC+AHEwXfAHIF3wBAB0ADAJQgDws2At8AlAKmAHIFpgA=\"}"
            }
        }
    }

</sup>

