# LicensingWinRT

For x64
```vb

        Dim HwidGetCurrentExSig() As Byte = New Byte() {&H48, &H8B, &HC4, &H4C, &H89, &H48, &H20, &H4C, &H89, &H40, &H18, &H89, &H50, &H10, &H48, &H89}
        Dim ActivateWindowsSig() As Byte = New Byte() {&H48, &H8B, &HC4, &H55, &H48, &H8D, &H68, &HA1, &H48, &H81, &HEC, &H0, &H1, &H0, &H0, &H48}
        Dim ConvertPartNumberToPfnSig() As Byte = New Byte() {&H40, &H55, &H53, &H56, &H57, &H41, &H54, &H41, &H56, &H41, &H57, &H48, &H8D, &HAC, &H24, &H10, &HFB, &HFF, &HFF, &H48}
        Dim ConvertPartNumberToPfnExSig() As Byte = New Byte() {&H4C, &H8B, &HDC, &H49, &H89, &H5B, &H8, &H49, &H89, &H6B, &H10, &H49, &H89, &H73, &H18, &H57, &H48, &H83, &HEC, &H30}
        Dim GetWindowsPKeyInfoSig() As Byte = New Byte() {&H48, &H89, &H5C, &H24, &H18, &H55, &H56, &H57, &H41, &H54, &H41, &H55, &H41, &H56, &H41, &H57, &H48, &H8D, &HAC, &H24}
        Dim GetContentIdSig() As Byte = New Byte() {&H4C, &H8B, &HDC, &H49, &H89, &H5B, &H8, &H49, &H89, &H6B, &H10, &H56, &H57, &H41, &H54, &H41, &H56, &H41, &H57, &H48}
        Dim GetContentId2Sig() As Byte = New Byte() {&H48, &H89, &H5C, &H24, &H18, &H55, &H56, &H57, &H41, &H54, &H41, &H55, &H41, &H56, &H41, &H57, &H48, &H8D, &H6C, &H24}
        Dim GetActiveWindowsSkuStatusSig() As Byte = New Byte() {&H40, &H55, &H53, &H56, &H57, &H41, &H54, &H41, &H55, &H41, &H56, &H41, &H57, &H48, &H8D, &H6C, &H24, &HE1, &H48, &H81}
        Dim GetDownlevelPkeyDataSig() As Byte = New Byte() {&H48, &H8B, &HC4, &H4C, &H89, &H48, &H20, &H48, &H89, &H48, &H8, &H55, &H56, &H57, &H41, &H54}
        Dim CreateSppNamedParamsSig() As Byte = New Byte() {&H48, &H8B, &HC4, &H48, &H89, &H50, &H10, &H48, &H89, &H48, &H8, &H53, &H56, &H57, &H48, &H83, &HEC, &H30, &H48, &HC7}
        Dim DoesSkuIdMatchInstalledSkusSig() As Byte = New Byte() {&H48, &H8B, &HC4, &H55, &H56, &H57, &H41, &H54, &H41, &H55, &H41, &H56, &H41, &H57, &H48, &H8B, &HEC, &H48, &H83, &HEC}
        Dim EvaluateProductKeySig() As Byte = New Byte() {&H40, &H55, &H53, &H56, &H57, &H41, &H54, &H41, &H55, &H41, &H56, &H41, &H57, &H48, &H8D, &HAC, &H24, &HA8, &HF6, &HFF}
        Dim GetPid4FromRegistryInternalSig() As Byte = New Byte() {&H4C, &H8B, &HDC, &H49, &H89, &H5B, &H8, &H49, &H89, &H73, &H20, &H57, &H48, &H83, &HEC, &H30, &H49, &H83, &H63, &H18}
        Dim GetProductKeyFromRegistrySig() As Byte = New Byte() {&H48, &H89, &H5C, &H24, &H8, &H48, &H89, &H74, &H24, &H18, &H57, &H48, &H83, &HEC, &H20, &H8B, &HF9, &H48, &H8B, &HF2}
        Dim GetProductKeyTypeFromRegistrySig() As Byte = New Byte() {&H48, &H89, &H54, &H24, &H10, &H53, &H56, &H57, &H48, &H83, &HEC, &H20, &H48, &H8B, &HF1, &H33, &HDB, &H48, &H8D, &H4C}
        Dim GetProductKeyInformationSig() As Byte = New Byte() {&H40, &H55, &H53, &H56, &H57, &H41, &H54, &H41, &H55, &H41, &H56, &H41, &H57, &H48, &H8D, &HAC, &H24, &H98, &HFA, &HFF, &HFF, &H48, &H81, &HEC}
        Dim GuidFromStringSig() As Byte = New Byte() {&H48, &H89, &H5C, &H24, &H8, &H48, &H89, &H74, &H24, &H10, &H57, &H48, &H83, &HEC, &H20, &H48, &H83, &HC8, &HFF, &H33, &HF6, &H48, &HFF, &HC0}
        Dim InstallProductKeySig() As Byte = New Byte() {&H48, &H8B, &HC4, &H55, &H41, &H54, &H41, &H55, &H41, &H56, &H41, &H57, &H48, &H8D, &HA8, &H38, &HFD, &HFF, &HFF, &H48, &H81, &HEC, &HA0, &H3}
        Dim IsUpgradeProductKeySig() As Byte = New Byte() {&H48, &H89, &H5C, &H24, &H18, &H48, &H89, &H74, &H24, &H20, &H57, &H48, &H81, &HEC, &H40, &H5, &H0, &H0, &H48, &H8B, &H5, &H93, &H25, &H9, &H0, &H48, &H33, &HC4}
        Dim IsProductKeyAddOnSig() As Byte = New Byte() {&H48, &H89, &H5C, &H24, &H18, &H48, &H89, &H74, &H24, &H20, &H55, &H57, &H41, &H56, &H48, &H8B, &HEC, &H48, &H83, &HEC, &H60, &H48, &H8B, &H5}
        Dim ReadProductKeyFromRegistrySig() As Byte = New Byte() {&H40, &H55, &H53, &H57, &H48, &H8B, &HEC, &H48, &H83, &HEC, &H30, &H48, &H83, &H65, &H38, &H0, &H44, &H8B, &HC1, &H48}
        Dim RunClipUpSig() As Byte = New Byte() {&H40, &H55, &H53, &H56, &H57, &H41, &H54, &H41, &H56, &H41, &H57, &H48, &H8D, &H6C, &H24, &HF0, &H48, &H81, &HEC, &H10, &H1, &H0, &H0, &H48}
        Dim SafeAddSig() As Byte = New Byte() {&H48, &H89, &H5C, &H24, &H8, &H48, &H89, &H74, &H24, &H10, &H48, &H89, &H7C, &H24, &H18, &H41}
        Dim SafeMulSig() As Byte = New Byte() {&H48, &H89, &H5C, &H24, &H8, &H48, &H89, &H74, &H24, &H18, &H89, &H54, &H24, &H10, &H57, &H48}
        Dim HwidCPUDataCollectorSig() As Byte = New Byte() {&H48, &H89, &H5C, &H24, &H10, &H55, &H48, &H8B, &HEC, &H48, &H83, &HEC, &H50, &H48, &H8B, &H5, &HC4, &H1A, &H8, &H0}

```

to use:
```vb
 Dim pDll As IntPtr = LoadLibrary("LicensingWinRT.dll")
        If pDll <> IntPtr.Zero Then
            Dim hMod = GetModuleHandle("LicensingWinRT")
            If hMod = IntPtr.Zero Then
                Console.WriteLine(Marshal.GetLastWin32Error())
            End If
            Dim modinfo As New MODULEINFO
            If GetModuleInformation(GetCurrentProcess(), hMod, modinfo, Marshal.SizeOf(modinfo)) = True Then
                Dim byteMod(modinfo.SizeOfImage - 1) As Byte
                Marshal.Copy(hMod, byteMod, 0, modinfo.SizeOfImage)
                Dim dwAddress As UInteger = SearchBytePattern(HwidGetCurrentExSig, byteMod)
                If dwAddress <> 0 Then
                    Dim pAddressHwidGetCurrentEx = hMod + dwAddress
                    Dim HwidGetCurrentExFunc As HwidGetCurrentEx = CType(Marshal.GetDelegateForFunctionPointer(pAddressHwidGetCurrentEx, GetType(HwidGetCurrentEx)), HwidGetCurrentEx)
                    Dim structHWID(7) As Byte
                    Dim byteHWID(63) As Byte
                    Dim Key As IntPtr
                    Dim PID2 As IntPtr
                    Dim ppbValue As IntPtr
                    Dim pcbValue As UInteger
                    Dim hHwid = HwidGetCurrentExFunc(Key, PID2, structHWID, byteHWID, ppbValue, pcbValue)
                    If hHwid = 0 Then
                        'byteHWID:3E 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
                    End If
                End If
            End If
            Dim hFree As Boolean = FreeLibrary(pDll)
        Else
            Debug.Print(Marshal.GetLastWin32Error())
        End If


    Public Function SearchBytePattern(ByVal pattern() As Byte, ByVal bytes() As Byte) As Integer
        Dim matches As Integer = 0
        For i As Integer = 0 To bytes.Length - 1
            If pattern(0) = bytes(i) AndAlso bytes.Length - i >= pattern.Length Then
                Dim ismatch As Boolean = True
                Dim j As Integer = 1
                Do While j < pattern.Length AndAlso ismatch = True
                    If bytes(i + j) <> pattern(j) Then
                        ismatch = False
                    End If
                    j += 1
                Loop
                If ismatch Then
                    Return i
                End If
            End If
        Next i
        Return matches
    End Function
    
    <UnmanagedFunctionPointer(CallingConvention.Cdecl)>
    Private Delegate Function HwidGetCurrentEx(ByRef key As IntPtr, ByRef PID2 As IntPtr, ByVal addrHWID As Byte(), byteHWID As Byte(), ppbValue As IntPtr, cbValue As UInteger) As Integer
    <DllImport("kernel32", SetLastError:=True)>
    Function LoadLibrary(ByVal lpFileName As String) As IntPtr
    End Function
    <DllImport("kernel32.dll")>
    Public Function FreeLibrary(ByVal hModule As IntPtr) As Boolean
    End Function
    <DllImport("kernel32.dll", CharSet:=CharSet.Auto)>
    Public Function GetModuleHandle(ByVal lpModuleName As String) As IntPtr
    End Function
    <StructLayout(LayoutKind.Sequential)>
    Public Structure MODULEINFO
        Public lpBaseOfDll As IntPtr
        Public SizeOfImage As UInteger
        Public EntryPoint As IntPtr
    End Structure
    <DllImport("psapi.dll", SetLastError:=True)>
    Function GetModuleInformation(ByVal hProcess As IntPtr, ByVal hModule As IntPtr, ByRef lpmodinfo As MODULEINFO, ByVal cb As UInteger) As Boolean
    End Function
    <DllImport("kernel32.dll")>
    Function GetCurrentProcess() As IntPtr
    End Function
```
