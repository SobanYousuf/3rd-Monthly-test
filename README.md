# 3rd-Monthly-test
Input a string and output the character most used in the string

    Sub Main()
        Dim Str1 As String
        Dim nextchar As String
        Dim counter As Integer

        Console.WriteLine("Enter string : ")
        Str1 = Console.ReadLine

        For counter = 1 To Len(Str1)
            nextchar = Mid(Str1, counter, 1)

            Loc(Str1, nextchar) = 0


            Console.WriteLine(" " & nextchar)


        Next

        Console.ReadKey()


    End Sub

End Module
